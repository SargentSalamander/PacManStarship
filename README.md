PacManStarship
==============
# Starship Fontana #

This is project is based on a game written in C++ using the SDL library. The original game is available at https://github.com/AidanDelaney/StarshipFontana.

The features I have added are:
*Static walls. The player cannot pass through walls.
*A Score.
*Coins that disappear once collected.



## Installation ##
Requirements: SDL development libraries installed on your system.  

The easiest way to compile is to use a command-line

"$g++ -c src/*.cpp -std=c++0x -I/usr/include/sigc++-2.0/  \-I/lib64/sigc++-2.0/include/"

`$ g++ -o starship src/Main.o -lSDL -lSDL_image`

to run the game enter:

`$ ./starship`
 
from the top-level directory.  The game will expect to find the
`assets` directory under its current working directory.
