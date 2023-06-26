# Face Recognition using OpenCV

This repository contains a Python script that performs real-time face and eye detection using OpenCV's cascade classifiers. The script captures video frames from a webcam and applies face and eye detection algorithms to identify and draw rectangles around the detected faces and eyes.

## Prerequisites

- Python 3.x
- OpenCV (cv2) library
- Cascade classifier XML files for face and eye detection

## Installation

1.Clone the repository:

```bash
https://github.com/Mohshaikh23/Face-Recognition-using-OPENCV.git
```

2.Install the required dependencies:

```bash

pip install opencv-python
```

3.Download the cascade classifier XML files:

```bash
- [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
- [haarcascade_eye_tree_eyeglasses.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye_tree_eyeglasses.xml)
```

Save these files in the `haarcascade` directory.

## Usage

1.Navigate to the project directory:

```bash
cd face-recognition
```

2.Run the script:

```bash
python face_detection.py
```

3.The script will access the webcam and display the live video stream with face and eye detection. Rectangles will be drawn around the detected faces and eyes.

4.Press 'q' to quit and exit the program.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
