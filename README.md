CUDA-N-Queens
=============

Famous AI problem of N number of Queens solved in CUDA with brute-force for N=10.


How to use
============

Compile (you need to install the CUDA Toolkit first)

>$ nvcc queen.cu -o queen -arch=sm_21 CUDA.cu

Then run it

>$ ./queen


Alternatively

>$ gcc queen.c -o queen -lm
>$ ./queen
