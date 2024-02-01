The project involes 2 parts:

- First Part:

The aim here is to perform unmixing on each one of the pixels in the image with
nonzero label, with respect to the 9 endmembers (obtained after the execution of the
attached python code) using the following five different spectral unmixing methods:
(a) Least squares (as it was presented in the class),
(b) Least squares imposing the sum-to-one constraint
(c) Least squares imposing the non-negativity constraint on the entries of θ
(d) Least squares imposing both the non-negativity and the sum-to-one constraint on
the entries of θ.
(e) LASSO, i.e., impose sparsity on θ via 𝑙1 norm minimization.


- Second Part:

In this case, we consider also the image pixels with non-zero class label. The task is to
assign each one of them to the most appropriate class, among the 9 known classes. To
this end four classifiers will be used: (i) the naïve Bayes classifier, (ii) the minimum
Euclidean distance classifier, (iii) the k-nearest neighbor classifier and (iv) the Bayesian
classifier. # Spectral_Unmixing_Classification
