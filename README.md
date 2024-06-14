# Hand Tracking using OpenCV and MediaPipe

This Python script utilizes OpenCV and MediaPipe to detect and track hands in real-time using a webcam feed.

## Video Demo

![Hand Tracking Demo GIF](handDetector.gif)

## Dependencies

Make sure you have the following dependencies installed:

- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)

## Usage

1. Clone this repository to your local machine.
2. Ensure you have Python installed on your system.
3. Install the required dependencies mentioned above.
4. Run the `hand_tracking.py` script.
5. A webcam window will open showing the real-time hand tracking. Landmarks and connections on detected hands will be highlighted, and the frame rate (FPS) will be displayed on the top left corner of the window.

## Customization

You can customize the behavior of the hand detection and tracking by modifying the parameters in the `handDetector` class constructor (`__init__()` method) in the `hand_tracking.py` script. Parameters such as `mode`, `maxHands`, `detectionCon`, and `trackCon` can be adjusted according to your requirements.

## Author

[Chethiya Galkaduwa](https://github.com/chey97)

## License

This project is licensed under the [MIT License](LICENSE).
