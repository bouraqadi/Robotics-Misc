# Nao Writer

This folder provide Choregraph source code developed as part of a 2015 student project by Pierre Milin and Timothée Scherrer.
The goal of the project was to make Nao humanoid robot write some words.
This was performed by defining motions for individual letters. Then, to write words, blocks for individual letters are performed separated by motions to move the paper. 

## Setup

Nao should have the pen attached to the left hand.
The right had will push a tray that holds the paper.
A video of the demo is available [https://youtu.be/PDHDNxRDSqY?t=54]

## Folder Demo

- ANNEE.crg: makes Nao write the word ANNEE which means YEAR in french
- NAO ANO ONA OAN.crg: example of 3 letters words
- Nao2015-Choregraphe.crg: main file. Includes blocks for individual letteers + blocks to push the tray with the paper sheet.

## Folder Block behaviors

This folder includes 1 file for each basic behavior.

- There are 6 files, one for each letter: A, E, I, N, O, V
- PositionInitiale.crg: Makes Nao go to the initial position
- PousserFeuilleX.crg: those are variants of pushing the paper
