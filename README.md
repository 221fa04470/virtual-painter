🎨 Virtual Painter – Gesture-Based Drawing by Harsha Reddy
Virtual Painter is a professional-grade digital painting application developed by Harsha Reddy. It enables users to draw using hand gestures or mouse input. Using OpenCV and MediaPipe, this project turns any webcam into an interactive, touch-free drawing canvas.

If you find this project helpful or inspiring, please consider ⭐ starring the repository and supporting its growth!

🌟 Why Star This Repository?
Increases the visibility of my work

Encourages further development and feature upgrades

Supports open-source innovation for creative tech

🔗 GitHub Repository
Click here to Star

✨ Features
🧠 Gesture + Mouse Support: Draw with your fingers or the mouse

🛠️ Drawing Tools:

Brush

Eraser

Rectangle (outline and filled)

Circle (outline and filled)

Line Tool

🎨 Color Palette: 12 vibrant preset colors

🖌️ Brush Size Adjustment: Fine control using + and – buttons

🖐️ MediaPipe Hand Tracking: Pinch gesture to draw or place shapes

🧼 Canvas Clearing: Instantly reset your workspace

🖥️ Clean UI: Interactive top-panel with tool and color selection

✨ Smooth Experience: Uses point averaging for stable line rendering

🖥️ System Requirements
Python 3.6+

Webcam (internal or external)

Libraries:

OpenCV (cv2)

MediaPipe

NumPy

🔧 Installation
bash
Copy
Edit
git clone https://github.com/221fa04470/virtual-painter.git
cd virtual-painter
pip install opencv-python numpy mediapipe
python virtual_painter.py
🎮 How to Use
Mouse Mode:

Click buttons to select tools/colors

Drag to draw, click-drag-release for shapes

Gesture Mode:

Move index finger to interact with UI buttons

Pinch gesture to draw or shape

Release pinch to stop drawing

Open hand to clear the canvas

🧠 Behind the Scenes
OpenCV handles video input, frame overlays, and UI display

MediaPipe detects and tracks hand landmarks

NumPy manages drawing canvas arrays

deque is used for smoothing cursor motion

Gestures are recognized using distance logic (e.g., pinch = index + middle finger close)

🛠️ Customization
🎨 Add colors in the colors array

🖌️ Modify brush_size values for finer control

🧰 Add tools in the tools[] list and define drawing behavior

📐 Adjust UI layout in the setup block

🤝 Contributions
I welcome your ideas, improvements, and bug fixes!

Fork the repo

Create a new feature branch

Submit a pull request

Don’t forget to ⭐ the project to show your support!

🙏 Acknowledgements
OpenCV – Real-time computer vision support

MediaPipe – Advanced hand tracking

NumPy – Numerical computation backend

<p align="center">Made with ❤️ by Harsha Reddy, for creators, students, and digital art lovers</p> <h3 align="center">Happy Painting! 🎨🖐️</h3>
