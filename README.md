# Pong Game

A local two-player paddle game built with Python's `turtle` module. Each player moves a paddle to return the ball. When the ball passes a paddle, the other player scores and play resumes from the centre.

## Play

Use Python 3 with Tk support and run this command from the repository root.

~~~bash
python3 pongball.py
~~~

| Player | Up | Down |
| --- | --- | --- |
| Left paddle | W | S |
| Right paddle | Up arrow | Down arrow |

Click the game window to give it keyboard focus. The script attempts to play collision audio through macOS `afplay` using a local `bounce.wav` file. Supply your own file if you want sound.
