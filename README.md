# CUDA-Matrix-Multiplication

Two versions of the code-- both parallelized-- one still works better than the other (matrixmul.cu >> simpleMatMult.cu) 
because of the use of __shared__ memory for a thread block, that saves time from the read operations for the same rows and columns over and over.

