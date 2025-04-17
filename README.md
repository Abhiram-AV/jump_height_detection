# 🏃‍♂️ Jump Height Estimation with MediaPipe

This project estimates how high a person jumps using real-time video analysis. It uses **MediaPipe** for pose estimation and **OpenCV** for video processing.

---

## 🔍 Features

- Real-time body tracking using your webcam
- Measures jump height in **centimeters**
- Automatically detects takeoff and landing
- Counts total number of jumps
- Displays height of the most recent jump

---

## 📦 Requirements

Install the following packages:

pip install mediapipe opencv-python 

▶️ How to Run
Clone or download the project.

Run the script:
jump_height_detection.py
Make sure your webcam is connected.

🧠 How It Works
Uses MediaPipe Pose to detect hip landmarks

Tracks vertical hip movement

Converts vertical displacement to real-world units (cm)

Detects jump events using thresholding

Displays jump count and height in the live video feed

💡 Future Improvements
Automatic person height estimation for better scaling

Export jump data (CSV/Excel)

Smooth out noisy motion with better filters

Add GUI for user interface

🤝 Contributions
Pull requests are welcome! If you find a bug or want to improve this, feel free to fork the repo and submit a PR.
