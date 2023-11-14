# Helmet Detection System

## Overview

The Helmet Detection System is a computer vision project that identifies the presence of helmets in images or video streams. Utilizing deep learning techniques, specifically the YOLO (You Only Look Once) model, and OpenCV for image processing, this system enhances safety by automatically detecting whether individuals in a given scenario are wearing helmets.

## Features

- Real-time helmet detection using pre-trained YOLO model.
- Supports both image and video input.
- Easy integration with existing surveillance systems.
- Enhances safety measures by ensuring helmet compliance.

## Setup

1. **Download Pre-trained Model:**
   - Download the YOLOv3 weights and configuration file.
     ```bash
     curl -O https://pjreddie.com/media/files/yolov3.weights
     curl -O https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
     ```

2. **Install Dependencies:**
   - Install required Python libraries.
     ```bash
     pip install opencv-python
     ```

3. **Run the Helmet Detection Script:**
   - Execute the provided Python script to perform helmet detection.
     ```bash
     helmet_detection.py
     ```

## Usage

- Modify the script to process your specific image or video data.
- Adjust confidence thresholds and parameters for optimal results.
- Integrate the system with your surveillance or safety monitoring setup.

## Contributing

Contributions are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

---
**Note:** Ensure compliance with legal and ethical considerations when deploying surveillance systems. Respect privacy and adhere to applicable regulations.

