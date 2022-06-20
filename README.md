# Vehicle_Detection_and_Counting
Vehicle Detection and counting
This project focuses on detecting, tracking and counting vehicles by using Blob Detection tool. Pillow (Python imaging library) is used to process images from intial format to various levels described below.
> The accuray is approximately 85% depending on input footage. 

** What is Blob Detection? **
A Blob is a group of connected pixels in an image that share some common property ( E.g grayscale value ). Blob detection methods are aimed at detecting regions in a digital image that differ in properties, such as brightness or color, compared to surrounding regions. Informally, a blob is a region of an image in which some properties are constant or approximately constant; all the points in a blob can be considered in some sense to be similar to each other. The most common method for blob detection is convolution.

**Installtion**
Install requirements.txt with following dependancies
```
opencv-python-headless==4.2.0.32
numpy==1.19.3
Flask==1.1.1
Pillow==8.0.1
gunicorn
```
Numpy is used to map contour data on to the image. OpenCV headless library used for car classification models. 
```
set OpenCV_DIR="C:\OpenCV\build"
mkdir build
cd build
cmake -G "Visual Studio 12 2013" -D OpenCV_DIR=%OpenCV_DIR% ..  
```
