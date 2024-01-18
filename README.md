# Towers of Hanoi
## Introduction
Towers of Hanoi is a mathematical game invented in 1883 by a French mathematician, Edouard Lucas. The game consists of 3 vertical rods and some set of discs of various sizes with holes in the middle of the discs, allowing them to be stacked on the rods. The game starts with all of the discs on the leftmost rod with the smallest disc on top and each subsequent size stacked beneath it. The objective of the game is to move all discs such that the discs end up in the same setup on the rightmost rod while following 3 rules:
- Only one disc can be moved at a time.
- Any disc can be moved on to an empty rod.
- Any disc can be moved on to a rod containing a disc such that the disc being moved is smaller than the disc it is being moved on top of.

## Starting the game
The game is run through a command-line interface. In order to start the game, navigate to the directory where the 'hanoi.py' file is saved and input 'python3 hanoi.py ' into the command line.

## Gameplay
The game will first ask how many discs you would like to play with. For beginners, it is recommended you play with 3 discs to become familiar with the rules (2 discs is a trivial solution so 3 is the minimum allowed response). Input the desired number of discs as an integer and press enter.

The game will load with 3 stacks and all discs loaded into the left stack in descending order, which will be displayed to you.

On each turn you will be required to input the FROM and TO stack in that order, choosing from (L)eft, (M)iddle and (R)ight for each. After each input the game will display the current stacks.

The game goes on until the win condition is reached: all discs are in the right stack in descending order.
