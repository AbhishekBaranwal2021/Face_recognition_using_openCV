# Face_recognition_using_openCV
## IMPORTANT REQUERMENT
1. Face_recognition (Helps to Recognize and manipulate faces)
2. Open CV (It helps for image processing and performing computer vision tasks)
3. Numpy(It helps and provides multidimension array to perform mathematical operationn)
4. OS(This module help to interect with the operating system)

## DATASET
* Hear we take the data as an image(jpg format) and store it into a folder and then give the path of that folder. 

## WORKING
* We use a pre-existing model named as "Face_recognition"
* Taking the realtime image in the form of video with the help of OPENCV.
* Identifing the face feature from the given image and identify the unique feature of a particular person.
* PREPROCESSING ON INPUT DATA:- with the help of face_recognition module we encode or say extract the feature of the given image(eye,nose,etc) .
* PREPROCESSING ON THE OUTPUT DATA:-With the help of the video_capture and OPENCV we extract the face from the frame image(resize it to get the required feature)and convert into RGB frame. 
* We create the boundary aroung the face.
* If it's in the known_face then display the "name" else display "Unknown" .

## IMPORTANT LINKS FOR BETTER UNDERSTANDING
* For "FACE_RECOGNITION":- https://pypi.org/project/face-recognition/
* For "OPENCV":- https://opencv.org/about/
