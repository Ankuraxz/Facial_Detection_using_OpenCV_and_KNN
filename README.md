# Facial_Detection_using_OpenCV_and_KNN
This project Takes your photo as data input where captured image is converted to a numpy array (3d-matrix) and is fed to the algo.. The Algo. forms various clusters based on photos of various people and when a test image is served, the algo. output the name of file that contains most compareable (similar) photos as of test image. In this case KNN is the classification algo, but SVM, NN can also be used.

3-D Cluster visualization
Project Pipeline

### Procedure of Running the Project
- Install python 3 and download all requirments
- To Collect Data:- Run Collection of Face data, and provide inputs
- To Test the algo,:- Use KNN for Face detection

### Drawback
- Haarcascade is not a SOTA detector
- Model works on Compairing Similarities, so additional threshold needs to be added, to stop misclassification. Eg. You and your father can be classified as 1 if Model doesn't have data of your father
- Any stranger will be classified as "Most similar face" in absence of threshold.

## Screenshots



