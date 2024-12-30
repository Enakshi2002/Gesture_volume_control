# Gesture_volume_control

## Introduction

This project is a real-time hand gesture recognition system designed to control the system's volume. Using computer vision techniques and hand tracking models, it provides a contactless and intuitive user interface.

---

## Features

- **Real-Time Hand Tracking**: Detects and tracks 21 hand landmarks using MediaPipe's hand-tracking model.
- **Gesture-Based Volume Control**: Adjusts the system volume based on the distance between the thumb and index finger.
- **Interactive Visualization**: Displays hand landmarks and dynamic volume levels in the application window.


---

## Tools and Technologies

- **Python**: Core programming language for building the application.
- **OpenCV**: Used for video capture and image processing.
- **MediaPipe**: Provides a pre-trained model for hand landmark detection.


---

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/gesture-volume-control.git
   cd gesture-volume-control
   ```

 2. **Instructions to Operate the Gesture Volume Control Program:

set up your environment as said in this video:
https://youtu.be/KJepCMc0WMo?si=PL3kAo_Q3Ll4Q6Fm

Install the required libraries by running in that environment:
pip install mediapipe opencv-python pyautogui numpy

Run the program using:
python mainproj.py 

---

## How It Works

1. **Hand Detection**:
   - MediaPipe detects hand landmarks in real-time video frames captured using OpenCV.

2. **Landmark Processing**:
   - The distance between the thumb tip (landmark ID 4) and the index finger tip (landmark ID 8) is calculated.

3. **Volume Mapping**:
   - The distance is mapped to a volume range (e.g., 0% to 100%) using a scaling function.

4. **Visualization**:
   - Displays hand landmarks, the calculated distance, and a volume bar in the application window.

---

## Project Structure

- **`handtrack_min.py`**: Module for hand detection and landmark processing.
- **`mainproj.py`**: Main script to integrate hand tracking and volume control functionality.

---

## Applications

- Contactless audio control for smart devices.
- Gesture-based interfaces for accessibility solutions.
- Integration into AR/VR systems for intuitive user interactions.

---

## Future Improvements

- Add gesture recognition for other system controls (e.g., brightness adjustment).
- Implement multi-hand gesture functionality.
- Integrate with smart home systems for broader control capabilities.

---

## Acknowledgments

- **MediaPipe**: For providing the hand-tracking model.







