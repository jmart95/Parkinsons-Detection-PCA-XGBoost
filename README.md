# Road Lane Line Detection
## Context
Lane detection is an essential element of self-driving cars and autonomous vehicles. Using lane detection, the vehicle will know where to go and avoid the risk of running into other lanes or getting off the road. This can prevent the car from drifting off the driving lane. 
## Dataset
* YouTube Video: Driving Mumbai - SoBo (https://www.youtube.com/watch?v=KWJaBJYJIjI)
    * Frames (https://drive.google.com/file/d/1e4cc4zFFna3Owyym6aq7ZXoquHA2l95O/view)
## Objective
Build a model to detect lane lines in real-time. We will do this using the concepts of computer vision using the OpenCV library.
## Steps
1. Load in Parkinson Dataset
2. Frame Mask Creation
3. Feature Engineering 
    * Image Thresholding
    * Hough line Transformation
4. Video Preparation

## Results

In this Python machine learning project, we learned to detect the presence of Parkinson’s Disease in individuals using various factors. We used an XGBClassifier for this and made use of the sklearn library to prepare the dataset. This gives us an accuracy of <b> 96.66%</b>, which is great considering the number of lines of code in this python project.


## References
* https://homepages.inf.ed.ac.uk/rbf/HIPR2/hough.htm
* https://www.analyticsvidhya.com/blog/2020/05/tutorial-real-time-lane-detection-opencv/
