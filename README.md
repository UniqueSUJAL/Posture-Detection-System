# Posture-Detection-System
This Python script uses the MediaPipe library to detect human posture from images or video streams. It calculates various angles and distances between key body landmarks to determine whether the person has a good or bad posture. If a bad posture is detected for a prolonged period, the system sends a notification alert.

# Features
Detects key body landmarks using the MediaPipe Pose model.
Calculates angles and distances to assess posture.
Notifies the user if bad posture is detected for an extended period.

# Requirements
Python 3.x
OpenCV (pip install opencv-python)
Mediapipe (pip install mediapipe)
Plyer (pip install plyer)

# Usage
Install the required libraries using pip.
Ensure your webcam is connected or specify the path to a video file in the code.

# Run the script.
A window will open showing the webcam feed or video playback with real-time posture assessment.
If a bad posture is detected for more than 10 seconds, a notification alert will be sent.
python posture_detection.py

# Customization
You can adjust the threshold angles for determining good or bad posture according to your preference.
Modify the notification message or title in the sendWarning() function to suit your needs.
Customize the video file path or webcam input as required.
# Credits
This project utilizes the following libraries:
OpenCV - For image and video processing.
MediaPipe - For pose estimation.
Plyer - For cross-platform notifications.
