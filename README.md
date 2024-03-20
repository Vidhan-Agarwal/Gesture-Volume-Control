## Hand Gesture Volume Control

This project implements a hand gesture-based volume control system using your webcam, OpenCV, Mediapipe and PyCaw libraries. Raise your thumb and index finger together to control the system volume.

**Features:**

* **Hand Tracking:** Utilizes a [hand_tracking_module.py](hand_tracking_module.py) file  to detect and localize your hand and fingers in the webcam feed.
* **Volume Control:** The distance between your thumb and index fingertip determines the volume level.
* **Visual Feedback:** A volume bar and percentage display provide visual cues for the current volume.

**Requirements:**

* Python 3.x
* OpenCV library (`pip install --upgrade opencv-python`)
* Mediaipipe library(`python -m pip install mediapipe`)
* PyCaw library(`pip install pycaw`)
* [hand_tracking_module.py](hand_tracking_module.py)

**Instructions:**

1. Download or clone the repository.
2. Install the required libraries.
3. Make sure you have `hand_tracking_module.py` in the same directory or adjust the path in the code (if necessary).
4. Run the application using `python hand_gesture_volume_control.py` (or the appropriate filename).
