# Music-Genre-Clustering

## Part A: Data Analysis

 - :fire: Perform the data analysis projects as instructured in the file Final.ipynb that you can find in the 'files' on Canvas, and describe your work and your thinking underlying your analysis in a write up of at most 2 pages. The 2-page limit is just for the writing. It excludes figures, plots and possible code.
 
## Part B: Methodology

-  :fire: Submit a 2-page write-up summary what you have learned in class about the use of eigenvectors and eigenvalues for unsupervised learning.

Eigenvalues and eigenvectors play a crucial role in unsupervised clustering and machine learning. Each eigenvector has an eigenvalue associated with it. Each eigenvector is just the original vector scaled by a constant equivalent to the eigenvalue associated with the eigenvector. In principal component analysis, a popular dimension reduction technique, the covariance matrix of the original matrix X is calculated and diagonalized. The reason for diagonalizing the covariance matrix is because it is symmetric. In addition, the process of diagonalization simply decomposes the covariance matrix into three parts, an eigenvector multiplied by a diagonal matrix with eigenvalues on the diagonal, and then multiplied by the same eigenvector transposed. The eigenvectors are called the principal directions of the data and the projections of the data on the principal directions are called principal components. Each principal component is a linear combination of the original data and the coefficients are known as loadings. These loading values are then used to determine which variables contribute most to the principal component being examined.
	Spectral clustering is another method which employs eigenvalues, eigenvectors, and their properties. First, we calculate the Laplacian matrix and then find the k eigenvectors corresponding to the k smallest eigenvalues of the Laplacian. 

