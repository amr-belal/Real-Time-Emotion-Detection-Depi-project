# Real-Time Emotion Detection from Webcam
This project implements a real-time emotion detection system that captures live video feed from a webcam, detects faces, and classifies emotions using a pre-trained deep learning model. The application is built with Streamlit for an interactive and easy-to-use web interface.

### Features
- Real-time Webcam Feed: Captures and processes video frames in real-time.
- Face Detection: Uses Haar Cascade for detecting faces in each video frame.
- Emotion Classification: Classifies emotions such as Angry, Happy, Neutral, Sad, and Surprised using a pre-trained deep learning model.
- Interactive Interface: Simple and intuitive interface built using Streamlit.

### Installation Steps
- Clone the project repository to your local machine.
- (Optional) Set up a virtual environment for dependency management.
- Install the required dependencies listed in the requirements.txt file.
- Download the pre-trained emotion detection model and place the architecture and weight files in the project directory.
- Run the Streamlit application to start the real-time emotion detection interface.
### Usage Instructions
- Launch the application to access the web-based interface.
- Click the button to activate the webcam feed.
- The system will detect faces in the video stream and display the predicted emotions on-screen.
- Stop the webcam feed when done by unchecking the control button.
### Project Structure
- Main Application File: Contains the code to run the Streamlit web app and handle the emotion detection logic.
- Pre-trained Model Files: The deep learning model used for emotion classification, including the model architecture and its weights.
- Requirements File: Lists all the external libraries and dependencies required to run the application.
- Documentation: This README.md file to guide users on how to install and use the project.

### Emotion Categories
The application classifies the following emotions:

- Angry
- Happy
- Neutral
- Sad
- Surprised
  
### Requirements
- Python 3.x
- Streamlit for building the web interface.
- OpenCV for face detection and video capture.
- TensorFlow and Keras for loading and using the pre-trained emotion detection model.
- NumPy for handling array operations and image data.
### Acknowledgments
Special thanks to the developers of Streamlit and OpenCV for providing powerful tools to build and deploy the application.
The emotion detection model used is based on widely available pre-trained models for facial expression recognition.
