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


📊 Example Output
Input: Raw image
Output: Annotated image with bounding boxes stored in unique_detections/images/
Labels: YOLOv8 format stored in unique_detections/labels/

