TITLE : Classic Arcade Game
TABLE OF CONTENTS :
1)  About
2) Approach & Overview
3) Topics To Be Covered
      * Main Html Page 
      * Player JS Page
      * Pipe JS Page
      * Background JS Page
      * Game JS Page
      * STYLE CSS PAGE
4) How To Run


1) ABOUT : In this I'll build a Flappy JavaScript game! I will guide you through the source code with explanations.The main objective of the game is to go through pipes without touching them while fighting against the gravity that is pulling you down constantly. The game gets infinitely harder as it gets faster.

2) APPROACH & OVERVIEW : 
* We will use an object-oriented approach to build the game as it helps separate the game logic and elements, breaks them into objects very nicely even though we are not going to instantiate too many objects.
* Each object will have draw and update methods. Draw methods will define how the object will look and the update method will define the object logic and its interaction with the physical world.
* Each method will be called every frame within the game loop.

3) TOPICS TO BE COVERED :
* MAIN HTML PAGE :  It defines the canvas that the whole JavaScript game will be drawn into, and loads necessary script and image files.
* PLAYER JS PAGE : Our first and main game object; the bird! Since the gameplay depends on gravity and how it affects the movement of the bird, this page will carry the bulk of the logic.
* PIPE JS PAGE : Pipes are essentially just some basic rectangular shapes that we do not want to hit. They start from the right side of the screen, then they move to the left by 4 pixels each frame. When they are outside of the viewport, they jump back to the right side of the screen to a random y position.
* BACKGROUND JS PAGE : Just like pipes, the background also travels to the left of the screen with a constant speed and it jumps back to its initial spot when it is outside of the screen.
* GAME JS PAGE : This is where everything comes together and the magic happens. In this file we will:
                      --  Capture the canvas element we defined in the HTML file and define how texts should be drawn.
                      --  Load the sprite sheet from the sprite element we included also in the HTML file
                     --  Define global game variables, flags, and instantiate objects
                     --  Add an event listener to track the up arrow button
                     --  Define the main game loop that calls update and draw methods of all the game objects that are instantiated
* STYLE CSS PAGE : This page contains some basic styling to center the game screen, and give it a phone screen feeling.

4) HOW TO RUN : 
* Open index.html in your browser.
* A mobile screen appears with black background.
* Hit Enter to play.
* Press up arrowkey multiple times to save the bird from pipes according to your need.
* The more you save the bird from the pipe the more you gain score.
* If the bird collides with the pipe the game ends and your score display on the screen.
* if you want to play more hite enter two times on the screen.
* Enjoy playing.


* 