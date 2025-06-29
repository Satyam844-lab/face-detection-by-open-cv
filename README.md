
Face Detection using OpenCV (Console App)
----------------------------------------

This Python script uses OpenCV to perform real-time face detection using your webcam.
It applies a Haar cascade classifier to detect faces in live video feed and draws green rectangles around them.

----------------------------------------
Features:
- Real-time webcam face detection
- Uses pre-trained Haar cascade model
- Simple and beginner-friendly script
- Press ESC to exit the app

----------------------------------------
Requirements:
- Python 3.x
- OpenCV (Install via: pip install opencv-python)

----------------------------------------
How to Run:
1. Make sure your webcam is connected.
2. Install OpenCV using pip if not already installed.
3. Run the script using:
   python face_detection.py

----------------------------------------
How It Works:
- Loads the Haar cascade classifier: haarcascade_frontalface_default.xml
- Opens webcam video feed using cv2.VideoCapture
- Converts frames to grayscale
- Detects faces using detectMultiScale()
- Draws green rectangles on detected faces
- Press ESC to quit


