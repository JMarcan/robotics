# CPPND: Snake Game

In this project, I had been extending a Snake Game
as part of the Udacity C++ Nanodegree.


## New Features
- User can choose starting speed for the game via console input
- User score is compared against the best score, the best score is saved into a file


## Addressed Rubric Points

Loops, Functions, I/O
- User can choose starting speed for the game via console input
- The best score is saved into a file
- The best score is loaded from the file, compared against the user score, and if user set a new record it's stored in the file 
- New functionalities are organized in functions

Object Oriented Programming
-
-
-

Memory Management - meet at least 3 criteria
- 
-
-

Concurrency - meet at least 2 criteria
-
-
-

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  >Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source. 
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.