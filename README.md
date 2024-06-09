# Game of Life

This is a simple implementation of Conway's Game of Life written in C++.

## Overview

[Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.

## Features

- Simple graphical representation of the game board.
- Configurable board size.
- Step through generations manually or automatically.

## Requirements

- C++11 or later
- [raylib library](https://www.raylib.com/) (A simple and easy-to-use library to enjoy videogames programming)

## Credits to

Inspirated with Programming With Nick and his tutorial [Conway's Game of Life tutorial in C++ & raylib - OOP](https://youtu.be/daFYGrXq0aw?si=TnnAfXES8tl2I8s9). 

Tutorial repository is [here](https://github.com/educ8s/CPP-Game-Of-Life-with-raylib).

Thank you.

## Controls

- `Left Click`: Add cell state (alive).
- `Right Click`: Remove cell state (dead).
- `Space`: Start/stop the simulation.
- `ENTER`: Clear / Reset the board.
- `Key up`: Increase the simulation speed.
- `Key down`: Decrease the simulation speed.
- `Key left`: Increase cell edges.
- `Key right`: Decrease cell edges.
- `F`: Toogle fullscreen ON/OFF.
- `C`: Turn on/off random colors.
- `Esc`: Exit the game.

## Config file

Some of the start up parameters can be adjusted in `config.ini` file. If file does not exist, it will be created during first lunch of the game with default parameters.