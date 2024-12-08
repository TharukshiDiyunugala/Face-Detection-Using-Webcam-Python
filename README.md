Face Detection Using Webcam with Python
This project demonstrates a real-time face detection and recognition system using Python, OpenCV, and the face_recognition library. The application captures video streams from a webcam, detects faces in real-time, and matches them with pre-encoded face data.
The system is designed to recognize a user’s face from a set of known faces and label them accordingly. When a registered face (such as the user’s own) is detected, the system successfully identifies and labels it with the person's name. However, when an unknown face is shown, it is detected and labeled as "Unknown."
Features
Real-time face detection and bounding box visualization.
Face recognition with pre-trained encodings for identifying known faces.
Interactive interface using OpenCV for live video feed display.
Simple and efficient error handling for smooth operation.
Technologies Used
Python: Core programming language.
OpenCV: For video capture and image visualization.
Face Recognition Library: For facial encoding, detection, and recognition.
NumPy: For efficient image processing and matrix manipulations.
How to Use
Clone the repository and set up the required dependencies using pip install -r requirements.txt.
Add face encodings and names to the known_face_encodings and known_face_names lists in the script.
Run the script and allow access to your webcam.
Press q to quit the application.
Applications
Security and surveillance systems.
Attendance and authentication systems.
Personalized user experiences.
