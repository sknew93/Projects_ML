# Projects_ML

## 1_PCA
Using PCA create a face recognition system. To
implement this, you can use LFW_peoples dataset provided in the scikit-learn library. Given
this dataset, use only those classes that have a minimum (use min_faces_per_person
= 70, resize = 0.4 ) 70 images (should give you only 11 classes). Given this subset
of images, apply PA to obtain the corresponding eigen face for each class. You can
additionally train a classifier for recognition purpose. 

## 5_EDGEDETECTION
Using OpenCV, first convert any image with varying ligh condition to a grayscale image. Now
implement edge detection first using the canny edge detection. Then apply simple thresholding
and also Adaptive/OTSU thresholding using OpenCV to see the working of each of these
methods. Once you obtain good results, use the obtained edge detection result as a mask to
give color to all the edges (if edges use the color from the original image, else leave it black
only.
