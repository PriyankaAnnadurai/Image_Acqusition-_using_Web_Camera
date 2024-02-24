# Image_Acqusition-_using_Web_Camera
## Aim
 
Aim:
 
To write a python program using OpenCV to capture the image from the web camera and do the following image manipulations.
i) Write the frame as JPG 
ii) Display the video 
iii) Display the video by resizing the window
iv) Rotate and display the video

## Software Used
Anaconda - Python 3.7
## Algorithm
### Step 1:
<br>

### Step 2:
<br>

### Step 3:
<br>

### Step 4:
<br>

### Step 5:
<br>

## Program:
``` Python
# Developed By: Priyanka A
# Register No: 212222240104

# i) Write the frame as JPG file




# ii) Display the video


import numpy as np
import cv2
cap=cv2.VideoCapture(0)
while True:
    ret,frame=cap.read()
    cv2.imshow('Video',frame)
    if cv2.waitKey(1)==ord('q'):
        break
cap.release()
cv2.destroyAllWindows()




## iii) Display the video by resizing the window





## iv) Rotate and display the video









```
## Output

### i) Write the frame as JPG image
</br>

![Screenshot 2024-02-24 134300](https://github.com/PriyankaAnnadurai/Image_Acqusition-_using_Web_Camera/assets/118351569/c7974234-a7ef-4df4-a18e-4c348bc8edcb)


</br>


### ii) Display the video
</br>

![image](https://github.com/PriyankaAnnadurai/Image_Acqusition-_using_Web_Camera/assets/118351569/d8655979-689f-4a2a-9194-04b4a2c41039)


</br>


### iii) Display the video by resizing the window
</br>

![image](https://github.com/PriyankaAnnadurai/Image_Acqusition-_using_Web_Camera/assets/118351569/1026b587-9bc9-4ae5-98ac-6d332ffe78bd)


</br>

### iv) Rotate and display the video
</br>

![image](https://github.com/PriyankaAnnadurai/Image_Acqusition-_using_Web_Camera/assets/118351569/71c2cc65-e266-4cd1-86f0-4cf15e193d0d)


</br>


## Result:
Thus the image is accessed from webcamera and displayed using openCV.
