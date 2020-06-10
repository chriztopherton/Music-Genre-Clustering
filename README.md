# Music-Genre-Clustering

## Part A: Data Analysis

 - :fire: Perform the data analysis projects as instructured in the file Final.ipynb that you can find in the 'files' on Canvas, and describe your work and your thinking underlying your analysis in a write up of at most 2 pages. The 2-page limit is just for the writing. It excludes figures, plots and possible code.
 
## Part B: Methodology

-  :fire: Submit a 2-page write-up summary what you have learned in class about the use of eigenvectors and eigenvalues for unsupervised learning.

https://docs.google.com/document/d/18OWMq6Arjc0C0iWAEcvrqW5NsTyR_X7VGg7NEQSXUEE/edit?usp=sharing

A fundamental and core aspect of unsupervised learning, and machine learning in general, is linear algebra, the derivation behind many clustering algorithms. When the problem is concerned with the idea of dimensions and linear transformations, matrices and vectors come into play. Transforming a matrix involves the principal direction in which it is “stretched”, defined by an eigenvector and the factor or quantity of the scale, given by the associated eigenvalue. 


PCA is one such dimension reduction technique that aims to project the original dataset onto a smaller subset of the initial dimension. The covariance matrix of the original matrix X, the original dataset, is calculated and diagonalized. The reason for diagonalizing the covariance matrix is because it is symmetric. In addition, the process of diagonalization simply decomposes the covariance matrix into three parts, an eigenvector multiplied by a diagonal matrix with eigenvalues on the diagonal, and then multiplied by the same eigenvector transposed. The eigenvectors are called the principal directions of the data and the projections of the data on the principal directions are called principal components. Each principal component is a linear combination of the original data and the coefficients are known as loadings. These loading values are then used to determine which variables contribute most to the principal component being examined.

Spectral clustering is another method which employs eigenvalues, eigenvectors, and their properties, in order to discover similarity measures in a dataset and assign unlabeled data to different groups or “clusters”. First, we calculate the Laplacian matrix and then find the k eigenvectors corresponding to the k smallest eigenvalues of the Laplacian.

