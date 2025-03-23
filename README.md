Real-Time Face Emotion Detection

This project uses OpenCV and DeepFace to perform real-time face detection and emotion recognition from a live webcam feed.

Prerequisites

Before running the script, ensure you have the following dependencies installed:

Required Libraries

OpenCV (cv2)

DeepFace

You can install them using pip:

pip install opencv-python deepface

How It Works

Captures video from the default webcam.

Detects faces using OpenCV's Haar cascade classifier.

Extracts the face region and analyzes emotions using DeepFace.

Displays the detected face with a bounding box and the dominant emotion label.

Press 'q' to exit the video feed.

Usage

Run the script using Python:

python script_name.py

Replace script_name.py with the actual filename of your script.

Error Handling

If the webcam fails to capture video, the script will print Failed to capture video and exit.

If an error occurs during emotion analysis, the script will print an error message but continue running.

Example Output

The script will display a live video feed with detected faces marked by rectangles and their corresponding emotions labeled above them.

License

This project is open-source and available for modification and distribution under the MIT License.
