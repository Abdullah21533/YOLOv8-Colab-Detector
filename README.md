# YOLOv8-Colab-Detector
# 🎯 YOLOv8 Colab Webcam & Image Detector

This repository provides an interactive object detection demo using the **YOLOv8 model** in **Google Colab**, allowing you to:
- 📸 Capture live images using your webcam
- 📁 Upload and analyze local image files
- ✅ Visualize real-time detection results with bounding boxes

Perfect for researchers, educators, and students who want to test YOLO models in an interactive environment—without needing local setup.

---

## 🧠 Features

- ✅ **Live Webcam Integration** in Colab via JavaScript
- ✅ **Image Upload Option** for inference
- ✅ **YOLOv8 Support** (custom `.pt` model upload)
- ✅ Lightweight and runs entirely in-browser
- ✅ Visualizes output directly using OpenCV (`cv2_imshow`)

---

## 📂 Repository Contents

YOLOv8-Colab-Detector/
├── README.md # Project overview and usage guide
└── yolov8_colab_detector.ipynb # Colab notebook for live object detection


## 🚀 Getting Started in Google Colab

### Step 1: Open the Notebook

Click to open the notebook: [▶️ Launch in Colab](https://colab.research.google.com/)

### Step 2: Upload Your YOLOv8 Model

Upload your trained YOLO model file (e.g., `best.pt`) when prompted:
```python
### ⬆️ Please upload your 'best.pt' YOLO model file.
Step 3: Choose Input Method
Click 📁 Upload Image to select and detect objects in a local image

Click 📸 Capture from Webcam to activate webcam and detect objects from live capture

### 📷 Example Demo
Input	Detection Output
Webcam/Image	

(Replace example_output.jpg with your real result if available)

### 📦 Dependencies
All dependencies are handled inside the notebook. If needed locally:

pip install ultralytics opencv-python ipywidgets nest_asyncio
### 🔒 Privacy Note
Your webcam stream is only accessed temporarily during capture via the browser and is never saved or transmitted. All detection is performed locally inside the Colab environment.

#### 📄 License
This project is licensed under the MIT License.
Feel free to fork, modify, and use for academic or personal projects.

### 🙌 Acknowledgments
Ultralytics YOLOv8

Google Colab

OpenCV and ipywidgets for visualization

### 💬 Contact
Created by [Muhammad Abdullah]
For collaborations or questions: [abdullah21533@gamil.com]
