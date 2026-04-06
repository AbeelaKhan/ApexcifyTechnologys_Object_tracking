# Real-Time Object Detection and Tracking in Python

This is a simple **real-time object detection and tracking** project where the system detects objects from a webcam or video file and tracks them with unique IDs.

---

## Objective

The goal of this project is to implement **real-time object detection and tracking** using a pre-trained YOLO model and a tracking algorithm like ByteTrack.

---

## Tools Used

- Python  
- OpenCV  
- Ultralytics YOLO (`ultralytics` package)  

---

## How the AI Works

- YOLOv8 detects objects in each video frame.  
- Detected objects are passed to the **ByteTrack tracker**, which assigns unique IDs to objects across frames.  
- Bounding boxes, class labels, confidence scores, and tracking IDs are drawn on the video feed.  
- The system processes frames in real-time for live video display.  

---

## How to Run

1. Make sure **Python is installed**.  
2. Install dependencies:

```bash
pip install opencv-python ultralytics
```
3. Run the main script:
```bash
python object_tracking.py
```

4. The webcam window will open showing detection and tracking.
5. Press "q" to quit the application.

---

## Features

- Real-time object detection from webcam or video file
- Bounding boxes with class labels and confidence scores
- Object tracking with unique tracking IDs
- Lightweight and optimized for real-time performance

## Learning Outcomes

- Understanding of object detection models (YOLOv8)
- Basic video processing with OpenCV
- Implementation of object tracking algorithms (ByteTrack)
- Real-time visualization of AI predictions

## Note
This project was created as part of an internship task for learning object detection and tracking.
