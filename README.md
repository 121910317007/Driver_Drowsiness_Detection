# Driver_Drowsiness_Detection
Using OpenCV and dlib, we are going to create a project to detect the drowsiness of driver from live video

PROJECT DESCRIPTION

The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.

The sample image is provided in the files provided (2.jpg)

And the 68-landmark detector data (.dat) file can be found in https://drive.google.com/drive/folders/14XqZ26tDKVgDfkdlUqVYpEKEvDxLeYiz?usp=sharing


THE WORKING OF THE PROJECT

As you can see in the provided image, the landmarks are detected using the detector.

Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.

Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.

PROCESS OF RUNNING THIS CODE

-Put code file and 68-landmark detector data (.dat) file in the same folder

-After running the source code, you will be asked to give the access to the webcam, allow this

-The live video frame pops up where it detects the thresholds of sleeping, drowsy and active



OUTPUT

output video in the same drive link
