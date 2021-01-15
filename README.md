# Sudoku_Solver
Repository for Sudoku Solver_Main
This repository is a on-display repository of the project Sudoku Solver.
This repo have some training/testing images and working videos.
To run the file in your system compile all the modules the call the last main function module.
Thank You :)

I have Used,
Tensorflow 2.3.1
Keras 2.4.0
numpy 1.18.5
as the project is developed using above versions, but can run on any stable versions. Hopefully.

# Procedure
Whole procedure can be devided in following steps - 
1. Image Extraction/Capturing
2. Extraction of Sudoku and Digit blocks from full Sudoku image
3. Extracting the Digits from image and creating an Unsolved sudoku
4. Solving the Sudoku
5. Creating sudoku array into image and Display it(Easiest)
there are many more steps in-between these steps like removing noise on the sudoku came
while capturing image. 

These noise can be like - 
1. Black blobs (mainly dots)
2. Lines of sudoku block came while cutting digit cells from the image

you have to take care of both the blobs and lines as these would definitely affect the reading of digit by deep learning Model.
