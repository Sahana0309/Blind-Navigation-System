# Blind-Navigation-System
YOLO Object Detection

Overview

This project implements real-time object detection using YOLOv3 (You Only Look Once) and OpenCV. It uses a pre-trained YOLO model on the COCO dataset to detect and classify objects in a live video stream.

Features

Real-time object detection

Uses YOLOv3 deep learning model

Implements Non-Maxima Suppression (NMS) to filter weak detections

Displays detected objects with bounding boxes and confidence scores

Requirements

Make sure you have the following installed:

Python 3.x

OpenCV (cv2)

NumPy

imutils

Install Dependencies

pip install opencv-python numpy imutils

Files in this Repository

main.py – The Python script for real-time object detection

coco.names – COCO dataset class labels

yolov3.cfg – YOLOv3 model configuration file

yolov3.weights – Pre-trained YOLOv3 model weights

How to Run the Project

Clone the repository:

git clone https://github.com/YOUR_GITHUB_USERNAME/YOLO-Object-Detection.git
cd YOLO-Object-Detection

Run the script:

python main.py

Press q to exit the detection window.

Example Output

When the script runs, it will open your webcam and detect objects in real-time. Detected objects will be displayed with bounding boxes and labels.

License

This project is open-source and available under the MIT License.

Author

Sahana
