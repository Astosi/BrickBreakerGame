# Brick Breaker Game

This repository contains a simple Brick Breaker game implemented using HTML5 Canvas and JavaScript.
How to Run

    Download or clone the repository.
    Create an HTML file and include the provided JavaScript code within a <script> tag.
    Add a canvas element with the ID "container" to the HTML file.
    Open the HTML file in your browser to play the game.

## Example of an HTML file:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Brick Breaker</title>
</head>
<body>
  <canvas id="container" width="640" height="480"></canvas>
  <script src="brick_breaker.js"></script>
</body>
</html>
```

## Gameplay

The goal of the game is to break all the colored bricks on the screen by hitting them with a ball. You control a paddle (or stick) at the bottom of the screen to prevent the ball from falling off the screen. The ball bounces off the bricks and paddle, and the game is over when the ball falls off the screen.
Controls

    Use the left and right arrow keys to move the paddle left and right.
    You can also control the paddle with your mouse by moving it left and right within the game area.

## Scoring

Each brick has a point value associated with it, and your score increases by the brick's point value when it's destroyed. The game is won when you have a score of 250 points.
Customization

You can customize the game by modifying the following variables in the JavaScript code:

    widthOfBricks: Width of bricks in pixels.
    heightOfBricks: Height of bricks in pixels.
    heightOfStick: Height of the paddle in pixels.
    ballColor: Color of the ball.
    stickW: Width of the paddle in pixels.
    stickH: Height of the paddle in pixels.

You can also add, remove or modify bricks in the bricks array. Each brick has the following properties:

    x: X-coordinate of the top-left corner of the brick.
    y: Y-coordinate of the top-left corner of the brick.
    color: Color of the brick.
    point: Point value of the brick.
    status: Brick status (1 for visible, 0 for hidden).
    obstacle: Optional property (if defined, the brick will not be destroyed when hit by the ball).

