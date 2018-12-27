# Machine-Learning-Collection

## Background Removal with SVD

This project removes a still background from a video using Singular Value Decomposition (SVD).

First, we construct a matrix M from the video, where each column is a flattened image. Then we perform a full SVD on M and take the first rank to reconstruct the background image. The remaining part is the moving part in the video without background.

We also performed a randomized SVD by performing SVD on a smaller matrix that has approximately the same range as our original matrix. This method gives us acceptable results in a much shorter time compared to the full SVD.

## Topic Modeling with SVD and NMF

This project is an application of Singular Value Decomposition (SVD) and Non-negative Matrix Factorization (NMF) on topic modeling.

We also make a comparison between a full SVD and randomized SVD using different methods.

## NMF from Scratch using SGD

This project is an application of Non-negative Matrix Factorization (NMF) on topic modeling. 

We show an example for scikit-learn's implementation of NMF and implement algorithms for NMF from scratch using Stochastic Gradient Descent (SGD) with Numpy and PyTorch.