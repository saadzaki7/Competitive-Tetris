# Competitive-Tetris
A two player turn based Tetris game that follows Object Oriented Programming fundamentals. Lead a team of 3 members to create Biquardris/Competitive Tetris as our final project for Object-Oriented Software Development (CS 246) course.

Due to academic integrity concerns the source code for this project is not made publically available, however below I have attached several screenshots of the game and would be happy to provide it upon request.

Incorporated Observer, Factory method, Decorator, and Model View Controller design patterns. It also used techniques such as Polymorphism, RAII and single responsibility principle.

## Unified Modeling Language (UML) Diagram:

We created a UML to serve as a guideline for planning out our program.

![UML not rendering](UML.png?raw=true "Title")

## Graphical and Text mode screenshots:


## Movement features:
All seven block types can be moved in all directions except up, rotated counter clockwise and clockwise all with correct collision detection.

Below is a demonstration of the rotation feature:

## Leveling up feature:
Each player can level up or down to adjust the probabilities of harder or easier blocks spawning, and presence of debuffs to increase points they earn once they clear row(s). There are 3 levels all of which leverages the Factory method design pattern.

## Score:
After filling up row(s) they are cleared and points are added into the player's score through the following equation:
### Points_added = (Current_level + Rows_cleared) ^ 2
In this case it was:
Points_added = (3+1)^2 = 16

There is also a CLI interface that lets you pass in files containing the block sequences for each player, starting level, game mode, and randomization seed. 


