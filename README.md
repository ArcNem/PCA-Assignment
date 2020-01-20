# PCA-Assignment

Generate 100 data-points from 3 5D Gaussian distributions. The class labels will
be decided accordingly. The mean vectors of the 3 Gaussians are:
- Class 1: [2 8 4 3 5]
- Class 2: [2 8 4 9 5]
- Class 3: [8 8 4 9 5]

Covariance matrix for all classes: Diagonal elements 2, 3rd and 5th rows to be
diagonal only, remaining rows will have 1 along off-diagonal.
Also generate 20 test vectors separately from each class.

### Tasks:

1. Classify the test vectors using KNN. Use library function for KNN. Vary K and calculate accuracy of test dataset.

2. Create a Decision Tree using training data. Use Library functions. Vary the depth of the tree and calculate accuracy of test dataset.

3. Now implement PCA on the training data to find 2 principal dimensions.

4. Carry out KNN classification of the test data after projecting them along these dimensions. . Vary K and calculate accuracy of test dataset.
