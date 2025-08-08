# 🖱️ Virtual Mouse using Hand Recognition

This project allows users to control the mouse using **hand gestures**, powered by computer vision. It uses a webcam to track hand movements and perform mouse actions like move, click, and drag — all without touching a physical mouse.

📌 Features

- Move cursor with hand motion
- Left click using specific finger gestures
- Drag and drop support
- Built with OpenCV and Mediapipe

🧠 Technologies Used

- Python
- OpenCV
- Mediapipe
- PyAutoGUI
- NumPy

🎯 How It Works

1. Captures real-time video from your webcam
2. Detects hand landmarks using **Mediapipe**
3. Maps hand position to screen coordinates
4. Performs mouse actions based on finger gesture recognition

🚀 Getting Started

1. Clone the repo
git clone https://github.com/Vaijayyantiik/virtual-mouse.git
cd virtual-mouse

2. Install required packages
pip install -r requirements.txt

3. Run the project
python virtual_mouse.py

📸 How it Works
- The webcam captures real-time video frames.
- MediaPipe detects hand landmarks.
- Index finger controls mouse pointer.
- A pinch gesture (index + thumb) simulates a left-click.
- Additional gestures can be added for scroll, right-click, etc.



