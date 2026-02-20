# ML_Project5_SVM
This project accomplishes image compression using SVD (Single Value Decomposition) and Reconstruction on uploaded images.

The workflow of the project is the following:
1. upload an RGB image
2. convert the image to grayscale
3. convert the grayscale image to a matrix (Numpy array)
4. perform SVD on the matrix using the np.linalg.svd() function for that
5. reconstruct the image using:
  * top k singular values. Use several values of k for this task
  * k singular values that are not top values, namely
        * middle k singular values
        * smallest k singular values.
6. display the original and reconstructed images
