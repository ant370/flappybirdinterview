

# Javascript flappy bird

This is the current working document for our version of flappy bird.

The technology used is Javascript/HTML and CSS.

The game should run in any modern browser, and all library functions used should be limited to those standard javascript libraries that come natively with each of the major browsers.

# Feature Requests

- Make the gap between pipes vary randomly between 60 and 120 pixels.
- Add collision between the pipes and the bird, the game should end when the bird collides with a pipe or the ground. (https://developer.mozilla.org/en-US/docs/Games/Techniques/2D_collision_detection)
- Pressing the Escape key should end the game
- Add a worst score keeper on the game over screen.
- Add multiple lives to the bird, allowing the bird to collide with the tunnels up to three times before the game ends. (../img/bird/b3.png could be used to show the player visually that a collision has occurred.) Perhaps the bird should be teleported to a safe location after collision? 
- Add randomly placed diamonds, that when collected, give the player +2 points. See ../img/diamond.png for a diamond assett.

# Bugs

- Flapping the bird over the top of the game screen causes the game to end. Only colliding with the floor should end the game.
- Score counter starts at -1 for some reason.
- Pipes are showing over the ground. They should be hidden behind the ground.
- Score counter doesn't work. (Perhaps related to collision?)
- Score counter seems to drift right when playing the game... we feel the score should be very stationary.