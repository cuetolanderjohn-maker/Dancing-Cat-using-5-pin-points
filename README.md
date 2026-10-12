# Dancing Cat using 5 pin points

A real-time computer vision application using OpenCV and MediaPipe to detect hand gestures (5 fingertips / open hand pin points) and trigger a dancing cat GIF overlay above detected faces or on screen.

## Features
- **5 Pin Points Hand Detection**: Tracks wrist and 5 fingertips using contour analysis and convexity defects.
- **Dancing Cat Animation**: Triggers dynamic dancing cat GIF overlay when open hand (pin points) is detected.
- **Face & Hand Spatial Tracking**: Smooth face bounding box tracking with fallback screen center positioning.
- **FPS & Gesture HUD**: Real-time performance metrics and visual tracking lines.

## Requirements
- Python 3.9+
- Dependencies:
  ```bash
  pip install opencv-python numpy pillow mediapipe
  ```

## Usage
Run the script:
```bash
python camcamcam.py
```
- Press `d` to toggle debug contour mask view.
- Press `q` to exit.
