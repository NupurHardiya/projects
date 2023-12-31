****Hand Gesture Recognition and Control Readme****



**Introduction**
This project demonstrates hand gesture recognition and control using the Mediapipe library in Python. The script captures video from the default camera, detects hand landmarks, and interprets specific gestures to trigger actions on the computer. In this example, a single-click action is performed using the index finger and thumb pinch gesture.

**Requirements**
Ensure you have the following dependencies installed before running the script:

mediapipe

cv2 (OpenCV)

numpy

win32api

pyautogui


Install these dependencies using the following command:

  **_pip install mediapipe opencv-python numpy pywin32 pyautogui_**



**How to Run**
1. Clone the repository or download the script (Hand_gesture_control.py) to your local machine.
2. Open a terminal or command prompt and navigate to the directory where the script is located.
3. Run the script using the following command:
      python hand_gesture_control.py

**Usage**
1. The script will open a window displaying the live webcam feed.
2. Hold your hand in front of the camera, and the script will detect hand landmarks using Mediapipe.
3. Perform the pinch gesture (index finger and thumb close together) to trigger a single click action.
4. The program will output "single click" in the console when the gesture is recognized, and a mouse click will be simulated.

**Troubleshooting**

If the script does not run as expected, consider the following:

1. Ensure your camera is properly connected and functional.
2. Adjust the **min_detection_confidence** and **min_tracking_confidence** parameters in the **mp_hands.Hands** initialization to fine-tune hand detection.

