Virtual Mouse and Volume Control using Hand Tracking
This project creates a virtual mouse and system volume controller using hand gestures. It leverages Computer Vision and Python libraries like Mediapipe for hand tracking, autopy for mouse control, and pycaw for volume adjustment, providing a seamless and touch-free interaction experience.

KEY FEATURES;
 > Virtual Mouse with autopy:

    > Move the mouse pointer using hand movements.
    > Perform left and right clicks with gestures.
    > Drag and drop functionality via pinch gestures.
> Volume Control with pycaw:

  > Adjust system volume by varying the distance between fingers.
  > Real-time feedback on volume levels.
Technologies Used:
Python for implementation.
OpenCV for real-time video processing.
Mediapipe for hand landmark detection.
autopy for controlling mouse actions.
pycaw for volume adjustments.


How It Works
Hand Tracking: Mediapipe detects and tracks 21 landmarks on the hand.
Mouse Control (autopy): Hand position is mapped to the screen, and gestures are converted into mouse actions like moving, clicking, and dragging.
Volume Control (pycaw): The distance between thumb and index finger determines the volume level, controlled programmatically.


Requirements:
Python 3.x

Libraries:
  pip install opencv-python mediapipe autopy pycaw comtypes
