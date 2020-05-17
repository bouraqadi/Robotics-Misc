# Nao Writer with Choregraphe

This folder provide Choregraph source code developed as part of a 2015 student project by Pierre Milin and Timothée Scherrer.
The goal of the project was to make Nao humanoid robot write some words.
This was performed by defining motions for individual letters. Then, to write words, blocks for individual letters are performed separated by motions to move the paper. A demo is provided in the video below.

[![Nao Writer](https://img.youtube.com/vi/PDHDNxRDSqY/0.jpg)](https://www.youtube.com/watch?v=PDHDNxRDSqY)

## Setup

Nao should have the pen attached to the left hand.
The right had will push a tray that holds the paper.

## Folder Demo

Contains the following Choregraphe files :
- ANNEE.crg: makes Nao write the word ANNEE which means YEAR in french
- NAO ANO ONA OAN.crg: example of 3 letters words
- Nao2015-Choregraphe.crg: main file. Includes blocks for individual letteers + blocks to push the tray with the paper sheet.

## Folder Block Behaviors

This folder includes 1 Choregraphe file for each basic behavior.

- There are 6 files, one for each letter: A, E, I, N, O, V
- PositionInitiale.crg: Makes Nao go to the initial position
- PousserFeuilleX.crg: those are variants of pushing the paper
