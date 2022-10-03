Title: Single User Pong (SUPong)

Author: Jan Klingel <jan.a.klingel AT t-online.de>
Date: 03.10.2022
Version: 1.0
Language: Commodore/Microsoft BASIC V2

Description: A clone of the 1972 Atari Pong game, written in BASIC V2 for the Commodore C64/C128. 

Usage: Just run the program, there is no setup; move the paddle up and down with a joystick in port 2. Try to block the bouncing ball with the paddle from reaching the left border.

Function: In text mode, the computer draws the border and the ball at its first position. Randomly the computer moves the ball in its first direction. Contact with the border will bounce the ball and change its direction, same when contacting the paddle. Every bounce will create a short sound. If the ball reaches the left border, the player lost and can restart the game or quit. 
The paddle is a simple sprite that changes its y position by pressing the joystick up and down.

Variables: 
BO - Character for border
CH - Character for the ball
CL - Collision detection (1=collision detected)
CO - Current column (1..38) 
DI - Direction the ball is taken initially
I - Index variable for FOR loop
IN$ - Input variable taken from keyboard
JO - Value of the joystick switches
RO - Current row (1..23)
SC - Start of screen memory
SID - Start of SID sound voice 1
SZ - Start address of sprite 0
X - Index variable for FOR loop
Y - Pointer to DATA block of sprite



