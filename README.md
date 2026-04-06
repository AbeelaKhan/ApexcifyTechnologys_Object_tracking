# Real-Time Object Detection and Tracking

This repository implements **real-time object detection and tracking** using YOLOv8 and OpenCV. The project detects objects from a webcam or video file and tracks them with unique IDs using ByteTrack.

## Features
- Real-time video input from webcam or video file
- Object detection using **YOLOv8** (`ultralytics` package)
- Object tracking using **ByteTrack**
- Bounding boxes, class labels, confidence scores, and tracking IDs displayed in real-time

## Requirements
- Python 3.8+
- OpenCV
- Ultralytics YOLO

Install dependencies with pip:

```bash
pip install opencv-python ultralytics

