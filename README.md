# PuzzleSolver
python program for solving a (already) digitalized puzzle with computer vision and classical algorithms

working on:
- detection of edges and corners of each piece
- categorizing the sides of each piece (male/female/edge/corner)
- combining pieces due to its geometry and colors
- comparing position of pieces with given picture

in the end, the program should be capable of solving a 1000-pieces jigsaw puzzle in moderate time by using home-level computer performance

At the moment, the whole task is done running a jupyter notebook.
It's refering to an an "img"-directory, where the example-JPGs are loaded from "img/teile_second". After first evaluations, images get colored and saved in directories "img/Error", "img/Normal", "img/Rand". At the moment, that's basically for visualization and seeing if evaluations were sucessfull.
This time-consuming process of loading and saving files will be excluded from the final version when it comes to time-optimization.

## the directory "img/teile_second" must exist and contain the reffered images
