# Pacman Factory

## Table of content

- [Description](#description)
- [How to Run the Application](#howtorun)
- [Roadmap of Future Improvements](#roadmap)
- [License](#license)
- [Demo](#demo)

## Description
This web application is an HTML/Javascript factory that creates a new Pacman when the Add PacMan button is pressed and adds it to a "game" div. It is then added to the array of Pacmen, which keeps track of the position and velocity of each one.  A Start Game button starts the reading of the Pacmen array of information.  Each Pacman is moved according to its random velocity and new position.   There is logic to ensure each Pacman does not go outside of the DOM box container.
You also need to make each pacman bounce off any wall it hits.

<img src="PacMan1.png">

## How To Run The Application

### About
This application is made up of 2 main files and an image directory
  - the index.html file which creates the divs for the game which includes 2 buttons,  Add PacMan and Start Game.  This file also the pacmen javascript file as SRC.
  - the pacmen.js file which includes the javascript functions including the 2 major ones,  MakePac() which is the Factory to make a PacMan at a random position with random velocity and update() which loops over the pacmen array to update the position and then moves the image in the DOM
  - the images directory contains Pacmen images,  2 with mouth open and 2 with mouth closed positioned to the left and to the right.

### Running the Application
 (1) You can download the 2 files and 1 images directory to your local drive.  Once installed in a directory, run the index.html file from a new web page OR you can run the application direct from github from the link, https://pamelaarcher.github.io/addpacmen/
 (2) Click on the Add PacMan button once for each pacman you want to add into the box on the page.  You can add as many as you want.
 (3) Click on the Start Game button.  This will start moving the Pacmen around the box based on a random velocity and position.  The update() function is repeatedly called which moves each Pacman by adding the random position to its location.   If it hits the edge of any side,  the pacmen will turn and move the opposite direction.

## Roadmap of Future Improvements
 (1) Change the image based on the direction it is moving
 (2) Change the image from open to close mouth as it moves across the page 

## License

MIT License

Copyright (c) 2022
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Demo

* [Pacman Factory Demo](https://pamelaarcher.github.io/addpacmen)
