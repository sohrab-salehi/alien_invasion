Alien Invasion

In Alien Invasion, the player controls a ship that appears at the bottom center of the screen. The player can move the ship right and left using the arrow keys and shoot bullets using the spacebar. When the game begins, a fleet of aliens fills the sky and moves across and down the screen. The player shoots and destroys the aliens. If the player shoots all the aliens, a new fleet appears that moves faster than the previous fleet. If any alien hits the player’s ship or reaches the bottom of the screen, the player loses a ship. If the player loses three ships, the game ends.

Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Prerequisities

Since this game is created using Pygame modules. You will need to install Pygame and its dependencies.

On Linux: Install the dependencies first using the packet manager.

$ sudo apt-get install python3-dev mercurial
$ sudo apt-get install libsdl-image1.2-dev libsdl2-dev libsdl-ttf2.0-dev
If you want to add sounds to the game, install the following libraries as well:

$ sudo apt-get install libsdl-mixer1.2-dev libportmidi-dev
$ sudo apt-get install libswscale-dev libsmpeg-dev libavformat-dev libavcode-dev
$ sudo apt-get install python-numpy
Then finally install Pygame using pip:

$ pip install --user hg+http://bitbucket.org/pygame/pygame
On OSX: Install the dependencies using Homebrew.

$ brew install hg sdl sdl_image sdl_ttf
see Troubleshooting for OSX's SDL bug

And for sound libraries:

$ brew install sdl_mixer portmidi
Ending by installing Pygame using pip:

$ pip3 install --user hg+http://bitbucket.org/pygame/pygame
On Windows

Find a windows installer that matches your version of Python. Run the installer if it is an exe and if there is an .whl file copy it to the project directory. Open a command window and navigate to the folder your copied your installer and install using pip.

> python -m pip install --user pygame-1.9.2a0-cp35-none-win32.whl
Installing

No installation is needed! To play the game, run the alien_invasion.py file using Python3 and enjoy!

Controls

Press the Return key(⏎) or click the 'Play' button to start
Steer the ship using arrow keys(←↑↓→)
Press 'q' to quit anytime.
Press 'p' to pause the game.

License

The MIT License (MIT)

Copyright (c) 2015

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
