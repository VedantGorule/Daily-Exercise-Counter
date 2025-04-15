# AI Trainer - Pose Detection

## Overview
AI Trainer is a Python application that utilizes OpenCV and MediaPipe to perform real-time pose detection. The application can track body movements and calculate angles, making it suitable for fitness applications, exercise tracking, and more.

## Features
- Real-time pose detection using webcam or video files.
- Calculates angles between specified body landmarks.
- Displays the detected pose and angles on the video feed.
- Counts repetitions of exercises based on arm movements.

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- NumPy

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name
Create a Virtual Environment (Optional but Recommended)

python -m venv .venv
Activate the Virtual Environment

On Windows:
bash
.venv\Scripts\activate

On macOS/Linux:
bash
source .venv/bin/activate
Install Required Packages

bash
pip install opencv-python mediapipe numpy
Usage
Run the Application

To run the application, execute the following command:
bash
python AITrainer.py
Interact with the Application

The application will open a window displaying the video feed from your webcam.
Press 'q' to exit the application.
