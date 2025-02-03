# Frame Selection and Object Detection using YOLOv5

## Overview
This project focuses on selecting key frames from a video using different techniques and performing object detection on them using **YOLOv5**. The objective is to extract meaningful frames and detect objects efficiently.

## Features
✅  Testing Three frame selection methods:
  - **Uniform Sampling**: Selects frames at equal intervals.
  - **Scene Change Detection**: Detects and selects frames where significant scene changes occur.
  - **Motion Analysis**: Selects frames with the highest motion activity.

✅ Object detection using **YOLOv5**
✅ Visualization of detected objects with bounding boxes

---

## Requirements
Make sure you have the following installed:

```bash
pip install opencv-python numpy scenedetect torch torchvision torchaudio
```

If using Google Colab, you may need to run:
```python
from google.colab.patches import cv2_imshow
```

---

## Installation
- Clone this repository:
   ```bash
   git clone https://github.com/Viplove0114/Frame-selection-and-object-detection.git
   ```

Feel free to contribute and improve this project! 🚀

