Middl Finder - The program is a structure in which, in a simple robot simulation environment, the robot moves until the front is blocked, places the beeper, then returns and places the beeper again, and then repeats certain actions.
1. while(frontIsClear()) { move(); } - The robot keeps moving forward until the front is blocked.
2. putBeeper();- When the front is blocked, the robot places a beeper in its current position.
3. turnAround(); - The robot rotates 180 degrees and returns to the starting position. Once you get back to the starting point, put a beeper again.
4. moveAndHandleBeepers() - The robot moves forward again, picking up the beepers one by one and moving them back, if there are any. This is repeated until the front is blocked.

After the robot moves to where the bifurr is not, it picks up the last remaining bifurr and ends.

The robot rotates to the right, moves until the front is blocked, then releases the biffer, and returns.

Make this process happen and place it in the middle.

