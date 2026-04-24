# Eye Controlled Mouse

This project uses your webcam to control the mouse pointer using eye movements. 

It leverages `OpenCV` for video capture, `MediaPipe` for high-precision facial landmark detection, and `PyAutoGUI` to control the mouse cursor.

## Features
- **Mouse Movement**: Tracks the movement of your eyes to move the mouse cursor across the screen seamlessly.
- **Mouse Clicks**: Performs a left mouse click when the user blinks or closes their left eye.

## Requirements
- Python 3.x
- `opencv-python`
- `mediapipe`
- `pyautogui`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Amal-05/eye_controlled_mouse.git
   ```
2. Install the required Python packages:
   ```bash
   pip install opencv-python mediapipe pyautogui
   ```

## Usage
Run the script from your terminal:
```bash
python eye_controlled_mouse.py
```

Ensure your face is well-lit and clearly visible to your webcam. You can terminate the program by selecting the video window and pressing any key.
