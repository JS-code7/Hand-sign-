🖐️ Hand Gesture Control Automation Tool
This project is a real-time hand gesture recognition system that uses your webcam to control your computer. By detecting the number of fingers held up, it maps specific gestures to keyboard actions like arrow key presses and spacebar input.


🚀 Features
Detects up to 5 fingers using MediaPipe.

Controls your computer via:

👉 1 Finger → Right Arrow (→)

✌️ 2 Fingers → Left Arrow (←)

🤟 3 Fingers → Up Arrow (↑)

🖖 4 Fingers → Down Arrow (↓)

🖐️ 5 Fingers → Spacebar (␣)

Works in real-time using webcam.

🧠 Tech Stack
Python

OpenCV

MediaPipe

PyAutoGUI

📦 Requirements
Install the necessary Python libraries:

bash
Copy
Edit
pip install opencv-python mediapipe pyautogui
💻 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/hand-gesture-automation.git
cd hand-gesture-automation
Run the script:

bash
Copy
Edit
python demo.py
Show different numbers of fingers to control your PC.

🔐 Permissions
Make sure your system allows webcam access and grants permission to control keyboard input.

🧪 Demo Use Cases
Control slides during a presentation hands-free.

Navigate media or web browsers via gestures.

Prototype for gesture-based accessibility systems.

📄 License
This project is open source and available under the MIT License.
