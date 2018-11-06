# Ricochet Robots Resolver

Ricochet Robots is a two dimensional puzzle game for one or more players; https://www.board-game.co.uk/product/ricochet-robots/. The goal is to navigate robots from their starting positions to targets on the board. A robot can move horizontally or vertically and continues until stopped by a wall or another robot. The goal of Ricochet Robots Resolver is to find the optimal solution for each target.

In the example below the target is the blue triangle as indicated by the targetin the middle of the board. This can be reached by the blue robot in five moves.

![](/images/ExampleBoard.jpg)

## Board Configuration

The board layout and robot starting positions can be varied.

There are eight double sided board sections. Each side is a tile; 16 tiles in total. Each tile is part of one colour group; red, green, blue or yellow. There are four tiles in each colour group. A valid board consists of four tiles and must have one tile of each colour. The number of possible board combinations is 4 x 12 x 8 x 4 = 1,536.

A complete set of tile images can he found [here](/Tiles.md).

There are 17 targets; each colour group has four targets and there is an additional multicoloured vortex target. Every tile contains four coloured targets and one tile in a valid board configuration will additionally contain the multicoloured vortex target. For clarity the targets will be named {colour}{shape} where colour is blue, green, red or yellow and shape is circle, hexagon, square or triangle. The multicoloured vortex target will be named vortex.

Each tile is an eight by eight square of cells. One cell is used to link tiles to create the board. The board is therefore 16 x 16 cells with four centre cells used for linking the board segments.

## Challenge

Given an image of the board taken using a smart phone
1. Identity the board configuration
1. Identify the robot starting positions
1. Solve to find the optimum solution for each target

The solution must run on a smart phone. It should take no longer than a minute to find all solutions.

## References

A search of github will show there are already several Ricochet Robots projects. This project aims to run on a smart phone and automate everything from just a photo of the board.