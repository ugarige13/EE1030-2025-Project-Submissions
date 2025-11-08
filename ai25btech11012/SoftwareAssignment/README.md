This project implements image compression using the Singular Value Decomposition (SVD) from scratch in C.
A grayscale image is treated as a matrix , where each element represents the pixel intensity (0 = black, 255 = white).
Using SVD, any image matrix can be factorized .
By retaining only the top k singular values and corresponding singular vectors, we can form a low-rank approximation of the image.
Used to find dominant eigenvalues and eigenvectors i used power iteration method which is explained clearly in the report .
The project successfully showed that as the rank k increases, the reconstructed image quality improves and the Frobenius error decreases, though at the cost of higher storage and computation. Conversely, smaller k values yield higher compression but visible loss of detail.
Overall, this work achieved the goal of compressing images using truncated SVD while reinforcing fundamental concepts of matrix theory, algorithmic implementation, and computational efficiency.
