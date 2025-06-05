# PoseEstimation

This Python project captures real-time webcam video to detect and visualize human body pose landmarks using MediaPipe Pose and OpenCV. It draws a full-body skeletal structure on the live feed, making it useful for fitness applications, posture analysis, and motion tracking.

🔧 Features
- Real-time video stream via webcam

- Human pose detection using MediaPipe’s deep learning model

- Drawing skeletal landmarks on key body parts (e.g., shoulders, elbows, knees)

- Simple OpenCV-based interface for visualization

🎯 How It Works
- Captures video from your webcam using cv2.VideoCapture().

- Converts each frame to RGB and processes it using MediaPipe Pose.

- If a person is detected, pose landmarks are drawn using mp_drawing.draw_landmarks().

- Press q to exit the application.

🛠️ Requirements
- Python 3.x

- OpenCV → pip install opencv-python

- MediaPipe → pip install mediapipe

🚀 Run the Script

_python pose_estimation.py_
