# AirClick
AirClick is a gesture-based virtual mouse application that allows users to control the mouse cursor, perform left/right clicks, double-clicks, and capture screenshots using hand gestures.The project leverages Python, OpenCV, MediaPipe, PyAutoGUI, and other libraries to create an intuitive, touchless interface for controlling your system.

Features
Mouse Control: Move the cursor by tracking index finger movements in real-time.
Left/Right Clicks: Perform left and right clicks using specific hand gestures.
Double Click: Execute a double-click with a unique gesture.
Screenshot Capture: Take screenshots with a predefined hand gesture.
Touchless Interaction: Provides an alternative to traditional mouse input, suitable for touchless and accessibility-focused environments.
Technologies Used
Python: Core programming language used for developing the application.
OpenCV: Used for real-time video capture and frame manipulation.
MediaPipe: Provides hand landmark detection and tracking.
PyAutoGUI: Enables mouse control (movement, clicks, double-clicks).
pynput: Simulates mouse button presses (left and right clicks).
NumPy: Performs mathematical calculations, such as angle and distance measurements.

Dependencies
OpenCV: For video capture and image processing.
MediaPipe: For hand landmark detection.
PyAutoGUI: For controlling mouse movements and clicks.
pynput: For simulating mouse clicks.
NumPy: For calculating angles and distances.
Usage
Run the application:


The webcam will open, and hand gestures will be detected. Perform gestures like:

Left Click: Specific gesture to perform a left mouse click.
Right Click: Another gesture to perform a right mouse click.
Double Click: Gesture for a double-click action.
Screenshot: Capture a screenshot with a predefined gesture.
To stop the application, press 'q' on the keyboard.

How It Works
Hand Landmark Detection: MediaPipe detects key points on the hand, such as the position of fingers.
Gesture Recognition: Using angles and distances between landmarks, the system recognizes specific hand gestures to map actions like mouse movement and clicks.
Mouse Control: PyAutoGUI moves the cursor based on the index finger’s position, while pynput simulates left and right mouse button presses.

Acknowledgements
MediaPipe for hand tracking and gesture recognition.
PyAutoGUI for mouse control automation.
OpenCV for video processing and real-time capture.
