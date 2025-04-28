✨ Gesture Runner
Gesture Runner is a fun AI-based game where players use real-world body gestures to control a runner — moving left or right based on simple motions!

This project uses live camera feed, real-time pose detection, and gesture recognition to map human movement into gameplay.

No keyboard, no mouse — just your body and the camera!

🚀 Features
Real-time gesture control with webcam

Move the character left or right by leaning

Play without traditional input devices

Built with OpenCV, MediaPipe, and Pygame

🧠 Technologies Used

Technology	Purpose
OpenCV	Captures live video from the webcam
MediaPipe Pose	Detects body landmarks (shoulders, arms, etc.) using AI
Pygame	Renders the game graphics and handles movement
About MediaPipe Pose:
MediaPipe uses deep learning (convolutional neural networks) to estimate human pose landmarks (like nose, shoulders, elbows, knees) from just a camera feed.
It detects 33 body keypoints using a lightweight model based on Google's BlazePose.

📂 How to Run
Install dependencies:

bash
Copy
Edit
pip install opencv-python mediapipe pygame
Run the game:

bash
Copy
Edit
python main.py
Make sure your webcam is connected!

📋 Practical Applications
Gesture-controlled games

Fitness or exercise apps

Virtual reality (VR) gesture tracking

Contactless interactive systems

AI-powered accessibility tools


⚡ Requirements
Python 3.7+

Webcam

Internet (for initial package installation)

🎯 Future Improvements (Optional ideas)
Add more gestures (like jump or crouch)

Improve gesture accuracy with smoothing

Add scoreboards, levels, or background music

Multiplayer via network

🔥 Let's move, not click! 🔥
