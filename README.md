# FaceDetection
Face Detection in Python using the Viola-Jones algorithm on the CBCL Face Database published by MIT's Center for Biological and Computational Learning. Learn how it works by reading my tuturial published in The Data Driven Investor on Medium.


# Data
The data is described at http://cbcl.mit.edu/software-datasets/FaceData2.html, and I downloaded from www.ai.mit.edu/courses/6.899/lectures/faces.tar.gz and compiled into pickle files.

Each image is 19x19 and greyscale. There are Training set:  2,429 faces, 4,548 non-faces
Test set: 472 faces, 23,573 non-faces 

- training.pkl
  - An array of tuples. The first element of each tuple is a numpy array representing the image. The second element is its clasification (1 for face, 0 for non-face)
  - 2429 face images, 4548 non-face images

- test.pkl
  - An array of tuples. The first element of each tuple is a numpy array representing the image. The second element is its clasification (1 for face, 0 for non-face)
  - 472 faces, 23573 non-face images


