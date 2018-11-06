# Ricochet Robots Resolver

Ricochet Robots is a two dimensional puzzle game for one or more players; https://boardgamegeek.com/boardgame/51/ricochet-robots. The goal is to navigate robots from their starting positions to targets on the board. A robot can move horizontally or vertically and continues until stopped by a wall or another robot. The goal of Ricochet Robots Resolver is to find the optimal solution for each target.

In the example below the target is the blue triangle as indicated by the targetin the middle of the board. This can be reached by the blue robot in five moves.

![](/images/ExampleBoard.png)

## Board Configuration

The board layout and robot starting positions can be varied.

There are eight double sided board sections. Each side is a tile; 16 tiles in total. Each tile is part of one colour group; red, green, blue or yellow. There are four tiles in each colour group. A valid board consists of four tiles and must have one tile of each colour. The number of possible board combinations is 4 x 12 x 8 x 4 = 1,536.

A complete set of tile images can he found [here](/Tiles.md)

There are 17 targets; each colour group has four targets and there is an additional multicoloured vortex target. Every tile contains four coloured targets and one tile in a valid board configuration will additionally contain the multicoloured vortex target.

Each tile is an eight by eight square of cells. One cell is used to link tiles to create the board.
