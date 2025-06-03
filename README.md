# ENGR103HArduinoGame
This is the repository for my arduino game that I created for my ENGR103H class


### Information about my game:
My game is based on rhythm games where you need to hit flashing lights when they pop up at a certain time. I made it so that lights will flow up from the bottom of each side of the board to the top. There are two different colors of lights, 2 different patterns for each level and 2 buttons. When a button is hit, if the light at the top of that side of the arduino is lit up, you will score a point and a tone will play, otherwise a point will be taken away. After 30 seconds, the game will move onto the next level out of three. After three levels it will say "Game over" with the built in speaker and then end the game. 

### Inputs
My main inputs are the left and right buttons.

### Outputs
My main outputs are sound when the player hits the button with the correct timing, as well as lights that are constantly on display. 
The output of sound corresponds to the input of the button being pressed and relies on checking if the top pin is lit. 

### Instructions:
- Hit upload
- Hit the left and right buttons when their side is lit
- Go for a high score!

