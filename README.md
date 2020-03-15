# Driver_Sleep_Detection_using_OpenCV

Every year thousands of road accidents occur due to drowsy driving and naps during driving. This must be treated with the same surmount importance and seriousness as seatbelt, airbags and etc. 
In this project, we developed a machine learning model that can recognize drivers who are sleepy / drowsy and buzz an alarm to wake them up and hence saving their lives. This has been demonstrated using a webcam of laptops which can be scaled up and implemented in any vehicle with minor environmental settings. 

### Ide: Spyder
### Language: Python version 3.6

### Algorithms and data used:
-------------------------
1. For detection and tracking of eyes : 
     Cascade Classifier
2. For prediction of drowsiness :
     Shape predictor_68_face_landmarks.dat file.
     Download from : https://bit.ly/2TQYraP


### Dependencies/Libraries:
-------------------------------------
1. OpenCV (cv2)
2. Numpy
3. os
4. imutils
5. time
6. dlib
7. argparse


### Steps to run the project:
-------------------------------------
1. WinPy --> open Spyder 
    You will see a console(Black window).
    DON'T close it, just minimize and wait.
2. Then you will see your spyder ide.
3. Now open your project folder and click on 
    the code file (.py file).
4. Run the file.
5. Remember to make sure you have alarm.mp3
    file in the same path as your code file.
6. To check without alarm use "pi_detect_drowsiness.py"
    file. Else use "pi_detect_drowsiness_with_alarm.py"
    file. 


  
 
