# BOWLING GAME

## Overview
The game consists of 10 frames as shown above.  In each frame the player has two opportunities to knock down 10 pins.  The score for the frame is the total number of pins knocked down, plus bonuses for strikes and spares.

A spare is when the player knocks down all 10 pins in two tries.  The bonus for that frame is the number of pins knocked down by the next roll.  So in frame 3 above, the score is 10 (the total number knocked down) plus a bonus of 5 (the number of pins knocked down on the next roll.)

A strike is when the player knocks down all 10 pins on his first try.  The bonus for that frame is the value of the next two balls rolled.

In the tenth frame a player who rolls a spare or strike is allowed to roll the extra balls to complete the frame.  However no more than three balls can be rolled in tenth frame.

## Task
Implement a basic UI for the bowling game.

1. A user must be able to define the number of each frame or randomly get one.
2. The rules mentioned above should all be respected.
3. The use of React is required.
4. You can use other libraries as you see fit.
5. Tests are optional.

## Example
![bowling_example](./bowling_game_image.png)
