🚀 YOLOv8 Object Detection System

This project implements an Object Detection System using YOLOv8 (from the Ultralytics
 library).
It supports real-time webcam detection, image detection, video detection, model training, exporting, tracking, segmentation, and pose estimation.
----------------------------------------------------------------------------------------------------------------
📌 Features

✅ Load YOLOv8 model of different sizes (n, s, m, l, x)

✅ Detect objects in:

 -Webcam stream

 -Single images

 -Video files

✅ Save processed images and videos with bounding boxes

✅ Real-time FPS counter for webcam detection

✅ Training support on custom datasets

✅ Export trained model to ONNX, CoreML, TFLite, etc.

✅ Advanced features:

 -Object Tracking (ByteTrack / BoTSORT)

 -Instance Segmentation

----------------------------------------------------------------------------------------------------------------
🛠️ Installation
Make sure you have Python 3.8+ installed.

1.Clone the repo:

git clone https://github.com/your-username/yolov8-object-detection.git
cd yolov8-object-detection

2.Install required packages:

pip install ultralytics opencv-python pillow matplotlib torch torchvision

----------------------------------------------------------------------------------------------------------------
▶️ Usage

Run the script:

python detector.py

1. Select Model Size

You will be prompted to select a YOLOv8 model size:

YOLOv8n → Nano (fastest, least accurate)

YOLOv8s → Small

YOLOv8m → Medium

YOLOv8l → Large

YOLOv8x → Extra Large (most accurate)

2. Choose Detection Mode

1 → Webcam Detection

2 → Image Detection

3 → Video Detection

3. Select threshold confidence (default 0.25)
  Enter value between 0.1 and 1


📷 Examples
Webcam Detection
python detector.py
# Choose model size and option 1

Image Detection
python detector.py
# Choose model size and option 2
# Enter image path (e.g., test.jpg)

Video Detection
python detector.py
# Choose model size and option 3
# Enter video path (e.g., video.mp4)

✨ Requirements

-Python 3.8+

-Ultralytics YOLOv8

-OpenCV

-NumPy

-PyTorch

-Matplotlib