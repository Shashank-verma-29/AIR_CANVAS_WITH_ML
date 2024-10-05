Air Canvas with Machine Learning
#**Overview**

Air Canvas with ML is a computer vision project that enables users to draw in the air by waving their fingers, with the help of machine learning and computer vision techniques. This project is built using OpenCV and Mediapipe in Python, allowing hand landmark detection and real-time drawing using hand gestures.

#**Features:**
Detect hand landmarks using Mediapipe.
Draw on a virtual canvas by tracking hand movements.
Create colorful, air-drawn art with simple hand gestures.
Easy to use and customizable for various applications.
This is a great project for anyone looking to build their portfolio in computer vision, machine learning, and real-time gesture tracking.

#**How It Works:**
Hand Detection and Tracking: The project uses Mediapipe’s hand landmark detection to track finger movements.
Motion Tracking: The forefinger’s coordinates are captured and stored over successive frames, forming the basis of the drawing.
Drawing on Canvas: As the hand moves in the air, the tracked points are drawn on a canvas, creating an image or pattern in real-time.
Color Detection: The video frames are converted into HSV color space for easier color detection, allowing users to "paint" with different colors by selecting ink buttons on the canvas.
#**Requirements:**
Ensure the following packages are installed in your Python environment:

Python 3.x
OpenCV (opencv-python)
Mediapipe
NumPy
#**You can install them by running:**
pip install opencv-python mediapipe numpy
#**Project Setup and Installation:**
#**Clone this repository to your local machine:**
git clone https://github.com/yourusername/Air-Canvas-with-ML.git
#**Navigate to the project directory:**
cd Air-Canvas-with-ML
Install the required dependencies:


#**How to Use:**
Run the Script: Once the script is running, your webcam will start capturing the video.
Hand Detection: Place your hand in front of the camera. Mediapipe will detect the hand landmarks, particularly the forefinger.
Start Drawing: Move your forefinger in the air to start drawing on the canvas. The points will be tracked and displayed as a drawing on the screen.
Select Colors: The canvas will have buttons for different ink colors. Use your finger to select the desired color.
#**Project Workflow:**
Read the video feed frame-by-frame.
Convert frames to HSV color space for better color detection.
Use Mediapipe's Hand Detection module to identify hand landmarks.
Track the forefinger coordinates and store them in an array for continuous frame drawing.
Render the drawing on both the video frames and the virtual canvas.
#**Customization:**
Adjust the hand detection parameters in the Mediapipe module to improve tracking accuracy.
Modify the drawing mechanics to incorporate more features, such as shape drawing or multi-color brushes.
Integrate additional gestures to clear the canvas, save drawings, or change canvas settings.
#**Future Enhancements:**
Add multi-hand support for collaborative drawing.
Implement gesture-based commands for undo/redo, clearing the canvas, or switching tools.
Allow saving and exporting drawings as image files.
#**Contributing:**
Contributions are welcome! Feel free to fork the project, open issues, or submit pull requests.


