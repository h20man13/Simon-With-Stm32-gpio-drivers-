# Simon-With-Stm32-gpio-drivers-
Simon puzzle game with my gpio drivers: There is a repository in my github
This game is designed for the nucleo-stm32f4re development board.
This game uses the reset button on the board to end a game.
This game uses the user botton on the board to start the game.

There are game buttons attached to pins pc13, pc10, pc3, and pc8.
The corresponding leds are attached to pins pc12, pc0, pc9, and pa10.

The user will start the game by pressing the user button.
After the user lets go of the user button it will flash a sequence. 
The user must flash the corresponding buttons in the exact order the lights were flashed.
Each round there will be another led added and the time required to "win" the round decreases each time.

When the game ends all of the leds will flash 4 times
