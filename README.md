# Face-Detection

An image is genrally a pixel, which can take on any value between 0 - 255.
A Simple Face Detection System Using OpenCV, Haar Feature and GrayScaling

# Theory

# What is Haar ?
Haar Cascade is a machine learning object detection algorithm used to identify objects in an image or video and based on the concept of ​​ features proposed by Paul Viola and Michael Jones in their paper "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001.
For example: the difference in brightness between the white & black rectangles over a specific area.

# What is GrayScaling ?
It is a process of Converting an image into a image where computer can understand the image.
The minimum values is 0 and te maximum value depends on the depth of the image.

# What is Cascade Classifier ?
Basically a Cascade Classifier tells OpenCv to 'what to look for in an image'.
A Haar Cascade Classifier takes positive and negative images to train the classifier.
where,
Positive Image - Only them images which we want to identify or classify
Negative Image - The images we do not want to Classify

## Parameter Tuning 

1.) Scale Factor :

=> some faces may be closer to the camera and appear bigger , scale factor can fix this by specifying

how much the image size is reduced at each image scale...

value ranges from 1.1 to 1.4

small - algorithm will be slow , since it is more thorough

high - faster detection but might miss some faces

2.) minNeighbors :

=> specifying how many neighbors each rectangle should have

value interval - 3-6

higher value - less detection with higher quality

3.) flags :

=> kind of heuristic, rejects images which have few edges

4.) minSize :

=> objects smaller are ignored

5.) maxSize :

=> objects larger are ignored

