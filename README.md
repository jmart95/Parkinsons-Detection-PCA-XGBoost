# Road Lane Line Detection
## Context
Lane detection is an essential element of self-driving cars and autonomous vehicles. Using lane detection, the vehicle will know where to go and avoid the risk of running into other lanes or getting off the road. This can prevent the car from drifting off the driving lane. 
## Dataset
* YouTube Video: Driving Mumbai - SoBo (https://www.youtube.com/watch?v=KWJaBJYJIjI)
    * Frames (https://drive.google.com/file/d/1e4cc4zFFna3Owyym6aq7ZXoquHA2l95O/view)
## Objective
Build a model to detect lane lines in real-time. We will do this using the concepts of computer vision using the OpenCV library.
## Steps
1. Read in Video Frames
2. Frame Mask Creation
3. Image Preprocessing
    * Image Thresholding
    * Hough line Transformation
4. Video Preparation

## Results

![ezgif com-gif-maker](https://user-images.githubusercontent.com/77241761/156899304-08e49bb9-9dec-4bbc-84f2-6a7aca75fd15.gif)


## References
* https://homepages.inf.ed.ac.uk/rbf/HIPR2/hough.htm
* https://www.analyticsvidhya.com/blog/2020/05/tutorial-real-time-lane-detection-opencv/
