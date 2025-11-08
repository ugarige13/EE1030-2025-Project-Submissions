This project implements Singular Value Decomposition (SVD) from scratch in C to perform image compression on grayscale .pgm images.
By reconstructing the image using only the top k singular values, it demonstrates how SVD can reduce image size while maintaining visual quality.
The program:
Reads an input image in .pgm format.
Computes the U, Σ, and V matrices of SVD.
Reconstructs compressed images at different ranks (k = 5, 20, 50, 100).
Saves the reconstructed images and prints the Frobenius reconstruction error.
To run this code for different greyscale images ,just insert the address in the code and run it to get different images 
