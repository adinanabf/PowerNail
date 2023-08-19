# Paint your nails with TensorFlow & OpenCV

This Python project is a handnail tracking application using TensorFlow and OpenCV. It uses a pre-trained object detection model to detect handnails in real-time from the camera (Webcam) video stream.

<!-- ![Demo](demo.gif) -->

## Requirements

- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Tkinter (for interface use)

## Installation

1. Clone the repository:

```bash
$ git clone https://github.com/adinanabf/PowerNail.git
$ cd PowerNail
```

(You can choose between 2a and 2b)

2a. Install the dependencies:

```bash
$ pip install tensorflow opencv-python numpy
```

2b. Install the requirements into a virtual enviroment

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ python3 -m pip install -r requirements.txt
```

## Usage

Run the `main.py` script to start the handnail tracking application:

```bash
$ python3 main.py
```

The application will begin capturing video from the camera and display the video frames with detected handnails in real-time. To exit the application, press the "q" key.

## Customization

If desired, you can adjust the parameters in the handnail_tracking.py file to suit your needs, such as the pre-trained model, colors used for the ellipses, and opacity.

## Credits

- The object detection model is based on the TensorFlow Object Detection API.

- Handnail detection is inspired by [Wen YongLiang's Nail Tracking algorythm](https://github.com/toddwyl/nailtracking).
