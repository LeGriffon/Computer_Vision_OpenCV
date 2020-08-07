# Computer Vision with OpenCV #
## This project is divided into two parts: ##

1. Character recognition using MNIST to process images and video stream

Character detection is implemented with OpenCV to preprocess ROI (region of interest), and the recognition function is realized by using a trained MNIST model to identify characters.

<img src="https://github.com/LeGriffon/Computer_Vision_OpenCV/blob/master/Demo/WX20190502-172332.png?raw=true" width="300">
<img src="https://github.com/LeGriffon/Computer_Vision_OpenCV/blob/master/Demo/WX20190502-172401.png?raw=true" width="300">


2. YOLO system object detection using COCO dataset and self-trained model for video stream processing

YOLO (You Only Look Once) is an object detector model. It is used to detect 80 objects in videos/images with the COCO dataset. It is later trained to include the detection of doors. The main challenges are:

 I. configuring hardware in order to train model since significant computational power is required to train a neural network 
 
 II. finding/creating a dataset of doors and labeling them to use in training 
 
 III. training a model.


Click image below to see video demo:

[![Watch the video](https://github.com/LeGriffon/Computer_Vision_OpenCV/blob/master/Demo/WX20190504-152915@2x.png?raw=true)](https://www.youtube.com/watch?v=U4y2hvrecSw)

Resulted self-labeled and self-trained door detection screenshots:

<img src="https://github.com/LeGriffon/Computer_Vision_OpenCV/blob/master/Demo/predictions.jpg?raw=true" width="200">
<img src="https://github.com/LeGriffon/Computer_Vision_OpenCV/blob/master/Demo/predictions1.jpg?raw=true" width="200">