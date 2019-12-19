# Connect 4 against CPU player

The classic game done as tiles rather than dropping discs. The CPU has a small percentage chance of playing randomly or adjacent to a previous tile. Win states are printed in the console. 


# Demo gif/images

Insert gifs


# Demo site 

[Sketch hosted at OpenProcessing](https://www.openprocessing.org/sketch/557501)


# Motivation

A challenge from a friend to test my understanding of programming and math.

First I attempted to make a more physics based simulation but decided that was adding another layer that was clouding my view of the game logic (See Connect 4 2 player physics project repository).

This project was an excellent reminder to “break the problem into smaller parts”. There were many sticky notes and pencil & paper modeling to get the right formulas.

A project that I’m proud to have completed without looking up connect 4 tutorials! 


# Build Status

Functions but breakable

At the time of this project I’d not yet studied error handling in depth so I pursued creating a playable version of the game and set aside error handling for a future project. 

Clicking on the grid works fine and the game progresses, but many errant clicks around the grid may cause an error. 


# Built with

Processing, a Java coding environment that lends itself for quick visuals. Or as explained at the [processing website](https://processing.org/)


    “Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts.” 


# Features

CPU player



*   Only legal moves to open grid spaces
*   aware of adjacent tiles and plays near them
*   percentage chance of random legal play

Object Oriented Programming


# Installation

The Processing Java Environment, a kind of overlay on the Java framework, requires the P3 Processing editor to write and execute with and can be found [here for download](https://processing.org/download/).


# Credits

I primarily learned to code again, after a long break since a couple college intro courses, from the [Coding Train](https://www.youtube.com/user/shiffman) YouTube channel featuring Daniel Shiffman, Associate Arts Professor at the Interactive Telecommunications Program at NYU’s Tisch School of the Arts. Using those lessons in object oriented programming, intermediate level functions, and other basics I was able to find the right equations to reference the squares to each other, and the basics of displaying the game. 