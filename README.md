# Object Detection using SSD - Readme

## Overview

This Python script utilizes Single Shot Multibox Detector (SSD) for real-time object detection in images or video streams. The SSD model is pre-trained on the MobileNet architecture and is capable of detecting various objects from the COCO dataset.

## Dependencies

Ensure you have the required Python packages installed. You can install them using:

```bash
pip install imutils numpy opencv-python
```

## Usage
### 1. Set Configuration:

Update the configuration parameters in the script according to your requirements:

  use_gpu: Set to True if you want to use GPU for acceleration.
  live_video: Set to True if using a live video stream; otherwise, set to False.
  confidence_level: Confidence threshold for object detection.

### 2. Download SSD Model Files:

Make sure to download the SSD model files:

  MobileNetSSD_deploy.prototxt
  MobileNetSSD_deploy.caffemodel
and place them in the 'ssd_files' directory.

### 3. Run the Script:

Execute the script using:

```bash
python your_script_name.py
```

  If using live video, it will access the default camera (or the camera specified by the index) for real-time detection.
  If live_video is set to False, it will process the video file specified (e.g., 'test.mp4').

### 4. Stop Execution:

Press Esc key to stop the script and close the detection window.

## Acknowledgments

This script is based on the MobileNetSSD architecture and utilizes OpenCV for image processing. Special thanks to the developers and contributors of the libraries used in this project.
