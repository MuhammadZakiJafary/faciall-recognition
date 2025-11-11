🧠 Facial Recognition with Eye Blink and Head Movement Detection
A real-time facial recognition application built using OpenCV, MediaPipe, and Python.
This project detects eye blinks, head movements (left, right, up, down), and overlays a green facial mesh for visualization.

🚀 Features
👁️ Detects eye blinking using Eye Aspect Ratio (EAR)
🧍‍♂️ Detects head movement directions (Left, Right, Up, Down)
💚 Draws a real-time green facial mesh using MediaPipe FaceMesh
🧩 Modular code design for easy understanding and updates
🎥 Real-time processing using webcam feed

🧰 Technologies Used
Python 3.8+
OpenCV – For real-time video capturing and image processing
MediaPipe – For facial landmark and mesh detection
NumPy – For mathematical operations and distance calculations

⚙️ Installation
Clone the repository:
git clone https://github.com/your-username/facial-recognition-blink-head.git
cd facial-recognition-blink-head

Install dependencies:
pip install opencv-python mediapipe numpy

Run the application:
python facial_recognition.py

💡 How It Works
The webcam captures live video frames.
MediaPipe detects 468 facial landmarks in real time.
The Eye Aspect Ratio (EAR) method identifies blinks.
The relative position of the nose, cheeks, chin, and forehead determines head direction.
A green mesh is drawn over the face for visualization.
Press ‘q’ to quit the application anytime.

📸 Demo Output
Action	Description
👁️ Blink	“BLINK DETECTED” appears on screen
👈👉 Head Turn	Displays “LEFT” or “RIGHT”
⬆️⬇️ Head Tilt	Displays “UP” or “DOWN”
💚 Mesh	Green lines show facial structure

Emotion and attention tracking

AR/VR face tracking and animation
