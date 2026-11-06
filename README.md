# YOLO Image Object Detection

Run a trained YOLO model against a local image using OpenCV and Ultralytics.

## Setup

```powershell
python -m pip install -r requirements.txt
```

## Usage

Place your input image next to the script and update `image_path`, or pass the script the path you want to analyze.

```powershell
python detect_image.py
```

The detected result is saved as `output.jpg`.
