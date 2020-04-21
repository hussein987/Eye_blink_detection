# Eye_blink_detection


## Description

This is a computer vision application that is capable of detecting and counting blinks in live video streams using facial landmarks from dlib and OpenCV. Moreover, the application detects the eye blinks that last for a certain duration (e.g 2 sec). Accordingly, an "Alert!" message will be displayed after the eyes being closed for more than 2 seconds.


## Running manual

1. Clone the repository to your local machine
2. Run the following command in the terminal at the directory where the repository is cloned:
   python3 main.py --shape-predictor shape_predictor_68_face_landmarks.dat
3. The application will use the defaul webcam of your computer to start the eye_blinks detection process as demonstrated above.


## NOTE

In the "demo.mp4" you can find a demostration for a running program
