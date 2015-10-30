# Project Title
##Graphics Programming Project 2015
###Sean Fitzpatrick

## Introduction
In this project I am required to design a running game on the HTML5 canvas as part of my project for Graphics Programming module, Semester 5 - year 3, Software Development.

## Ideas
So far I am thinking of something along the lines of some kind of Brick Break. This is to get the project up and running and the ideas will more than likely change as I am going through the project.

## Instructions
1. Create a file called index.html, which is the webpage the user will open to start the game.
You may use multiple files to organise your game, however the starting point must be index.html.
Create a the game using only HTML, CSS and JavaScript. Your starting index.html file might look like this:
    
    ```html
    <!DOCTYPE html>
    <html>
      <head>
        ...
        <style type="text/css"></style>
      </head>
      <body>
        ...
        <script type="text/javascript">
          ...
        </script>
      </body>
    </html>
    ```
    
1. Use a single Canvas element in index.html where all of your game is played and displayed.
    ```html
    <canvas id="gamecanvas"></canvas>
    ```

1. Use requestAnimationFrame to enable animation in your game.
    ```
    function step(t) {
      ...
      requestAnimationFrame(step);
    }
    ```

1. User interaction can either be through the mouse or keyboard or both. You may use jQuery to enable this, but ensure you include your jquery source file in your submission.
    ```js
    window.addEventListener("keydown", function(event) { 
        ...
    });
    ```

1. Comment all of your code so that it easily readable and understandable.
    
    ```js
    // ball is an object that represents a ball on the canvas.
    var ball = {
        // position is a property that represents the ball's position on the canvas.
        // It is an object itself with two properties, the x and y coordinates of the ball.
        position: {x: 10, y: 10}
        ...
    }
    ```
    
1. Include a README file with your code, written in [GitHub-flavoured](https://help.github.com/articles/github-flavored-markdown/) [MarkDown](https://help.github.com/articles/markdown-basics/).

    ```markdown
    # PacMan - an addictive 2D game
    ** by Tōru Iwatani **
    This is the README for PacMan, which includes details about the game including instructions detailing how to play the game.
    ```
    
1. Use Git to manage your source code - create a GitHub repository for your code and upload your game's code to it.

