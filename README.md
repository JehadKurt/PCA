# PCA
Task 1 (30 points) 
Load all the 25 images in the "\Eigenfaces\Train" 2. Display all the original faces in a 5X5 grid. Resize the images to 100X100 pixels for display only. 
3. Find the mean face image. Perform PCA on the training faces. 4. Display the mean face. Resize the mean face to 100X100 pixels for display only
4. ### Task 2 (30 points)

1. Select k = 2 eigenfaces (eigenvectors that correspond to the largest eigenvalues).
2. Reconstruct the training faces and display the reconstructed faces in a 5X5 grid.
3. Repeat the process for k = 5 and k = 15. For each k, reconstruct the training faces and display the reconstructed image in a 5X5 grid.
4. ### Task 3 (40 points)
1. Load all the test images from "\Eigenfaces\Test"
2. Project each image on the k = 2 eigenvectors and find if it's a face. If it's a face, find it's closest training image. Use euclidean distance to calculate distance.
3. Display all the results in an M X 2 table, where M is total no of test images. Each row of the table displays two images. The image on the left is the test image. The image on the right is it's closest image in the eigenfaces space. If an image is classified as a non-face, then the second column in the table should be blank.
4. Repeat the process and display the results for k = 5, k = 15.
