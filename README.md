# DROWSINESS DETECTION WITH OPENCV
### Detects and Alerts if the driver is starting to doze off.

Simple and effective blink detector using just Python, OpenCV and dlib.

 ## **Requirements: (with versions I tested on)**
 1. python          (3.7.3)
 2. opencv          (4.1.0)
 3. numpy           (1.61.4)
 4. imutils         (0.5.2)
 5. dlib            (19.17.0)

 ## **Commands to run the detection:**
 ```
 python detect_drowsiness.py \
	--shape-predictor shape_predictor_68_face_landmarks.dat \
	--alarm alarm.wav
```
