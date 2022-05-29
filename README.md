# FaceRecognition
Driver Drowsiness Detection System based on Face Recognition

It is a Computer Vision System which can automatically detect the driver drowsiness in real time video stream and generates an alarm if the driver appears to be drowsy. dlib has been used to detect human face using pre-defined 68 landmarks. After passing video feed to dlib frame by frame, it can detect left and right eye. It draws contours around it using openCV. Using Scipy's Euclidean function, it calculates Eye Aspect Ratio (EAR) and if EAR is less than 0.25, it sounds the alarm.

How to run:

* Create an environment in Anaconda and import the required libraries in the environment.

* Launch Jupyter Notebook. Paste the code, upload the .dat file and .wav file and run the code.

* Here you can find the dataset (.dat file) : http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
