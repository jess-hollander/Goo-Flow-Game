# Goo-Flow-Game
Goo Flow game inspired by the original [Pipe Dream](https://classicreload.com/win3x-pipe-dream-1991.html) video game.

This game was made using Racket in DrRacket using HTDP "[universe](https://docs.racket-lang.org/teachpack/2htdpuniverse.html)" and "[image](https://docs.racket-lang.org/teachpack/2htdpimage.html)" libraries. Source code can only be accessed by request due to plagarism standards. 

## Game Rules
- The game starts with a source goo pipe, pipes placed on the board, and a selection of pipes that are able to be placed (bottom of screen)
- You may place a pipe on the grid by left-clicking on the desired cell; you can only place the pipe shown on the very left of the available pipes display
- Once all pipes are placed, you may left-click the screen repeadetly to *propegate* the goo one pipe at a time starting from the source pipe
- If the next pipe does not connect to the current one within the flow, then the goo cannot *propegate* anymore and the game is over
- The goal of the game is to get as many pipes in the goo flow as possible
Notes: cross pipes can only flow in one direction and cannot act as a corner pipe

https://github.com/user-attachments/assets/bb1a2781-458f-409a-81a6-e9432adde9f5

## Instructions for Download (with requested source code)
1. Install and set up DrRacket application
2. Download *GooFlow.rkt* file
3. In DrRacket select the *File* tab, then *Open*, then select your *GooFlow.rkt* file

## Instructions to Play Game
1. Once *GooFlow.rkt* file is open
2. Click *Run* in top-right corner of the application to play the game
