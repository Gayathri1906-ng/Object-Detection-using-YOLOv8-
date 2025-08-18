# Object-Detection-using-YOLOv8-
This project implements Object Detection using YOLOv8 (You Only Look Once – Version 8).   The system detects multiple objects in images, annotates them with bounding boxes, and saves both the processed images and their YOLO-format label files.  
⚙️ Tech Stack  
- 🐍 Python  
- 🤖 YOLOv8 (Ultralytics) 
- 📷 OpenCV – For image processing  
- 📊 PyTorch – For deep learning model execution  

🚀 Features  
✅ Real-time object detection with YOLOv8  
✅ Pre-trained model (`yolov8n.pt`) included  
✅ Detects multiple classes (person, car, animal, objects, etc.)  
✅ Saves detection results in:  
   - `unique_detections/images/` (detected images with bounding boxes)  
   - `unique_detections/labels/` (bounding box coordinates in YOLO format)  
✅ Lightweight model (YOLOv8n) for fast inference  

 📂 Project Structure  

OBJECTDETECTION/
├── OBJECTDETECTION/
│ ├── ObjectDetection.py # Main script
│ ├── yolov8n.pt # Pretrained YOLOv8 model
│ ├── unique_detections/ # Results folder
│ │ ├── images/ # Annotated images
│ │ └── labels/ # YOLO format labels
└── .idea/ # IDE config files

🔧 Installation & Setup  

1. Clone the repository  
   git clone https://github.com/yourusername/object-detection-yolov8.git
   cd OBJECTDETECTION/OBJECTDETECTION
Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate    # On Linux/Mac
venv\Scripts\activate       # On Windows

Install dependencies
pip install ultralytics opencv-python torch torchvision

Run Object Detection
python ObjectDetection.py
📊 Example Output
Input: Raw image

Output: Annotated image with bounding boxes stored in unique_detections/images/

Labels: YOLOv8 format stored in unique_detections/labels/

📌 Future Enhancements
🔴 Webcam / Live video stream detection
📦 Integration with Flask/Django for web API
📱 Mobile deployment using ONNX/TFLite
📊 Performance comparison with YOLOv5/YOLOv7

📜 License
This project is licensed under the MIT License.

✨ Built with ❤️ using YOLOv8 + OpenCV + PyTorch
