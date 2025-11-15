# Real-time Ambulance Detection using MediaPipe and OpenCV

This Python script demonstrates real-time object detection using the MediaPipe framework and OpenCV. It captures frames from an IP camera stream, performs object detection on each frame, and displays the results with bounding boxes, labels, and scores.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- MediaPipe

## Installation

1. **Clone the repository:**

 ```bash
git clone https://github.com/your_username/realtime-object-detection.git
cd realtime-object-detection
```

2. **Install the required dependencies:**

 ```bash
pip install -r requirements.txt
```

## Usage

1. Modify the `url` variable in the script to point to your IP camera stream.
2. Run the script:

 ```bash
python realtime_object_detection.py
```

less
Copy code

3. Adjust the camera settings and tweak the object detection parameters as needed.
4. Press 'q' to exit the application.

## Configuration

- You can customize the object detection parameters and visualization settings directly in the script.
- Make sure to handle exceptions and errors gracefully, especially when dealing with network requests or camera stream issues.


## Acknowledgments

- MediaPipe: [https://mediapipe.dev/](https://mediapipe.dev/)
- OpenCV: [https://opencv.org/](https://opencv.org/)
- NumPy: [https://numpy.org/](https://numpy.org/)

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request for any improvements or feature additions.

