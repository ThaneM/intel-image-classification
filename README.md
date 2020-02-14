# intel-image-classification
UNCW Data Science project on image segmentation using Intel Image dataset from Kaggle

This is a jupyter notebook I wrote for a group project in one of my UNCW Data Science classes. The project tested simgle image segmentation on this Intel Image Classification kaggle project https://www.kaggle.com/puneet6060/intel-image-classification. I adapted an existing model someone had posted (https://www.kaggle.com/uzairrj/beg-tut-intel-image-classification-93-76-accur), but the segmentation was all original work.
The code splits the test and train images into a 3x3 grid. The model is trained on segments of the images and evaluated on segments of the test images. Three different methods are tested for combining scores from the 3x3 grid of image segments to classify the entire image.
