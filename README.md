# Spectral Unmixing and Classification Project

## Overview:
This project consists of two main parts aimed at analyzing hyperspectral image data: Spectral Unmixing and Classification.

### First Part: Spectral Unmixing
The objective of this part is to perform unmixing on each pixel in the image with a nonzero label, with respect to 9 endmembers obtained after executing the attached Python code. Five different spectral unmixing methods are employed:
1. Least squares (as presented in class).
2. Least squares imposing the sum-to-one constraint.
3. Least squares imposing the non-negativity constraint on the entries of θ.
4. Least squares imposing both the non-negativity and the sum-to-one constraint on the entries of θ.
5. LASSO, which imposes sparsity on θ via 𝑙1 norm minimization.

### Second Part: Classification
In this part, image pixels with non-zero class labels are considered. The task is to assign each of them to the most appropriate class among the 9 known classes. Four classifiers are utilized for this purpose:
1. Naïve Bayes classifier.
2. Minimum Euclidean distance classifier.
3. k-nearest neighbor classifier.
4. Bayesian classifier.

## Spectral_Unmixing_Classification Repository Structure:
The repository contains the following files and directories:

- **Python Code:** Contains the Python script used to obtain the 9 endmembers required for spectral unmixing.
- **Notebooks:** Includes Jupyter notebooks for each part of the project, detailing the implementation and analysis of spectral unmixing and classification methods.
- **Data:** Contains hyperspectral image data used for experimentation and analysis.
- **Results:** Contains output files and visualizations generated during the spectral unmixing and classification processes.
