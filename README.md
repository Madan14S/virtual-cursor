# Virtual Cursor

Control your mouse cursor using eye gaze and blinks with Python, OpenCV, and MediaPipe. This project demonstrates a simple eye‑tracking–based virtual mouse using a webcam.

🚀 Features

Real‑time eye tracking using MediaPipe Face Mesh

Smooth mouse movement mapped from gaze direction

Blink‑to‑click support

Works with a standard webcam

Lightweight and beginner‑friendly

🧰 Tech Stack

Python 3.8+

OpenCV – video capture & image processing

MediaPipe – facial landmark detection

PyAutoGUI – mouse control

▶️ Usage

Connect your webcam.

Run the script:

python Virtual-Mouse.py

Sit facing the camera in a well‑lit environment.

Move your eyes to control the mouse cursor.

Blink intentionally to perform a mouse click.

🧠 How It Works

Captures frames from the webcam using OpenCV.

Detects facial landmarks (especially eye landmarks) via MediaPipe.

Estimates gaze direction from eye landmarks.

Maps gaze movement to screen coordinates.

Detects blinks and triggers mouse click events using PyAutoGUI.
