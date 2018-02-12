# FaceDetect
Face detect python
# PURPOSE: 
Identify whether the input image is a face using pre-defined classifier from 
OpenCV. If it is print yes, and if its not a face print no.

# USE: 
PC with python and OpenCV installed. 
Along with haarcascade_frontalface_default.xml

To run the program in cmd/terminal type: <b> ./face-detect folderName/*.jpg </b>
or <b> ./face-detect image.jpg </b>

# PROGRAM: 

Face detection using Haar Cascades a method proposed by Paul Viola and Michael
Jones.
Takes image input and converts it from RGB (BGR) to grayscale or HSV and is 
checked using the face classifier XML by OpenCV and if a face structure is 
found, then the positions are returned, and prints yes, if there is no 
positions of face found, then the program prints no.
