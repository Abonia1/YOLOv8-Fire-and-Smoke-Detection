Fire and Smoke Tracking and Detection using YOLOv8
Introduction

This repository contains the code for tracking and detecting fires and smokes in real-time video using YOLOv8. The project uses a pre-trained YOLOv8 model to identify the presence of fire and smoke in a given video frame and track it through subsequent frames. The project is implemented using Python and OpenCV library.
Requirements

The following packages are required to run the code:

    Python 3.x
    OpenCV 4.x
    Numpy
    Cython
    CUDA (if using GPU for acceleration)

Usage

The project can be run using the following command:

css

python detect_smoke.py --input <path to input video> --output <path to output video>

The --input argument is required to specify the path to the input video. The --output argument is used to specify the path to the output video, which will contain the annotated frames with fire and smoke detections.
Result

The project can detect fire and smoke in real-time video with high accuracy. The detection and tracking performance can be improved by fine-tuning the YOLOv8 model on a custom dataset.
Conclusion

This project provides a simple implementation of fire and smoke tracking and detection using YOLOv8. It can be used as a starting point for more advanced projects and can be easily integrated into a larger system for fire and smoke monitoring.
