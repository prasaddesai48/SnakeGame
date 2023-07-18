It is a Java project that uses the inheritance, abstraction, and encapsulation concepts found in object-oriented programming. All the parts are organized using the JAVA Swing and AWT libraries.

It includes two main classes:

Snake (extends JFrame and invokes the GameControl class)
GameControl (extends JPanel)

The GameControl class provides the following methods:

GameControl() - It initializes Board Panel.
loadImages() - It loads images of the Snakehead, Snake body, and food.
initGame() - It initializes the Game.
checkCollision() - It checks the collision of the Snake's head with an obstacle (itself/food/wall).
locateApple() - It randomizes Apple's position every time.
gameOver() - It displays the Game Over massage and the player's score.

Functionalities:

The player can move the snake left, right, up, and down as per the given direction using respective arrow keys.
Whenever the snake eats food, its length increases by one, and a live score is displayed on the screen.
The food appears in a random position each time, either when the snake eats one or the new game is started.
When the snake collides with itself or with any of the walls, the "Game Over" message is displayed along with the player's score.

Design elements -

Snakehead: represented by a green dot.
Snake body: represented by a red dot.
Food: represented by an apple.


