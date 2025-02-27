# YOLOv11 Rectangle Shape Detection Model

## Overview
This project implements a **YOLOv11-based object detection model** trained on a custom dataset to accurately detect **rectangular shapes** in images. The model leverages deep learning techniques to provide high-speed, real-time detection, making it suitable for various applications such as industrial automation, computer vision, and robotics.

## Features
✅ **Trained on a Custom Dataset** for rectangle detection  
✅ **High Accuracy and Real-Time Performance** using YOLOv11  
✅ **Python Implementation** with PyTorch and OpenCV  
✅ **Supports Image and Video Processing**  
✅ **Scalable and Optimized for Future Enhancements**  

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/OmerKhan33/YoloV11_ShapeDetectionModel.git
cd YoloV11_ShapeDetectionModel
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
### **Run Inference on an Image**
```bash
python detect.py --source path/to/image.jpg
```

### **Run Inference on a Video**
```bash
python detect.py --source path/to/video.mp4
```

### **Live Webcam Detection**
```bash
python detect.py --source 0
```

## Training the Model
If you want to **train YOLOv11 on a new dataset**, follow these steps:

1. **Prepare the Dataset** (Ensure it follows YOLO format: images + labels)
2. **Modify the Training Configuration** in `config.yaml`
3. **Run Training**
4. **Save and Evaluate the Trained Model**

## Model Performance
| Metric         | Value |
|---------------|-------|
| mAP (IoU 0.5) | 95%   |
| FPS (GPU)     | 60+   |
| FPS (CPU)     | 20+   |

## Future Enhancements
🚀 Expand dataset for better generalization  
📈 Optimize inference for edge devices  
🛠️ Add support for detecting multiple geometric shapes  


## Contact
For queries or contributions, reach out via **omer.khan2384@gmail.com** or create an issue in the repository.


