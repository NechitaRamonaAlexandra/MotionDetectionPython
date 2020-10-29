# MotionDetectionPython

**Python-OpenCV**

This is a motion detection program, in which I used the OpenCV libraries for image processing. The application takes the input from the camera, and splits it into 4 windows:

- Gray frame, a slightly blurred imageused as intermediar for calculations
- Difference frame, which highlights the difference between the initial picture and the current recording image
- Threshold frame, a black and white frame based on intensity
- Color frame, the main window with the recorded image and the green rectangular highlights on the moving objects
