# Object_Detection_in_a_video_frame
Detecting objects using YOLOv3

# Detection of objects in a frame extracted from a video 
The code will take input video and extract a frame at the given timestamp. 

The name of video file should be the timestamp of the frame you want to extract. 
Example: if you want a frame at 1.92, then name your video file as 1.92. The extracted frame is saved as image.

Darknet YOLOv3 detection is applied to the image and give the output of detected objects.


# What is YOLOv3?
YOLOv3 (You Only Look Once, Version 3) is a real-time object detection algorithm that identifies specific objects in videos, live feeds, or images. YOLO uses features learned by a deep convolutional neural network to detect an object. Versions 1-3 of YOLO were created by Joseph Redmon and Ali Farhadi.
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.
YOLOv3 has been trained already on the coco dataset which has 80 classes that it can predict. We will grab these pretrained weights so that we can run YOLOv3 on these pretrained classes and get detections.

![image](https://user-images.githubusercontent.com/32535755/168033916-22a19a31-2982-4978-9a38-a72e5ab52833.png)
