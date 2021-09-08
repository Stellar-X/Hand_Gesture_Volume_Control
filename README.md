# Hand_Gesture_Volume_Control
Hello, I am Shubham JS Chaudhary.  

This is a project for a Python program to control system volume using hand gestures.  
  
The program detects a hand and based upon hand landmarks detects the hand gesture made.   
If the hand gesture is like widening or narrowing of gap between thumb and index finger (like zoom-in or zoom-out gesture), then system volume is increased or decreased resp.  
Also, if the hand gesture represents a closed fist, then the program is terminated.  
  
Python Libraries Used:  
1. OpenCV     :  Used for processing video to identify hand for gesture detection
2. Numpy      :  Used for performing fast mathematical operations on array objects
3. MediaPipe  :  Used for palm detection and identification of hand gestures using [hand landmarks](https://github.com/Stellar-X/Hand_Gesture_Volume_Control/blob/main/hand_landmarks.png) 
4. Pycaw      :  Used for controlling system audio


