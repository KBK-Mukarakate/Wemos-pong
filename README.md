# Wemos-pong
Year1, Semester 1 CMP 101 Wemos project.

This project implements a simple Pong game using a Wemos D1 Mini microcontroller, an OLED display, and a TM1638plus expansion board. The game is programmed using the Arduino IDE.

## Components Used
- Wemos D1 Mini microcontroller
- OLED display (128x64 pixels)
- TM1638plus expansion board
- Potentiometer (for paddle control)
- Buzzer (for sound effects)

## Libraries Used
- Streaming: Allows for easier serial printing.
- TM1638plus: Library for interfacing with the TM1638plus expansion board.
- Adafruit_GFX: Graphics library for OLED displays.
- Adafruit_SSD1306: OLED display driver library.

## Setup
- Connect the components according to the pin configurations specified in the code.
- Upload the code to the Wemos D1 Mini using the Arduino IDE.
- Ensure the correct libraries are installed in the Arduino IDE.

## Functionality
- The game consists of a ball bouncing between two paddles controlled by the player and the computer.
- The player's paddle is controlled using a potentiometer connected to the Wemos D1 Mini.
- The game ends when one of the players reaches a predefined score limit.
- Buttons on the TM1638plus board are used for game control, including pausing and quitting the game.

## How to Play
1. Turn on the Wemos D1 Mini.
2. Use the potentiometer to control the player's paddle.
3. Press the buttons on the TM1638plus board to pause or quit the game.
4. Try to keep the ball from passing your paddle while aiming to pass it past the opponent's paddle.
5. Score points by successfully hitting the ball past the opponent's paddle.
6. The game ends when one player reaches the maximum score limit.

## Additional Notes
- Adjustments to game difficulty can be made by changing variables such as paddle speed, ball speed, and maximum rally count.
- The OLED display provides real-time feedback on the game state, including scores and pause messages.
- Sound effects are generated using the buzzer, providing audio feedback during gameplay.

