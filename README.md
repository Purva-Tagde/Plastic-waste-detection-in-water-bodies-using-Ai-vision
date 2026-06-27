🌊 Plastic Waste Detection in Water Bodies using AI Vision

An AI-powered computer vision system that detects and classifies floating plastic waste in water bodies using YOLOv8 Object Detection. The project aims to support environmental conservation by enabling automated monitoring of rivers, lakes, and oceans through aerial or drone imagery.

📌 Project Overview

Plastic pollution has become one of the biggest environmental challenges, affecting aquatic ecosystems, marine biodiversity, and human health. Traditional monitoring methods are time-consuming, expensive, and prone to human error.

This project utilizes YOLOv8, a state-of-the-art object detection model, to automatically detect floating plastic waste from aerial images, enabling faster and more accurate waste identification for cleanup operations.

🎯 Objectives
Detect floating plastic waste in water bodies.
Classify different categories of plastic waste.
Reduce manual monitoring efforts.
Support real-time environmental monitoring.
Provide scalable and cost-effective waste detection.

✨ Features
AI-based plastic waste detection
Multiple object detection using YOLOv8
Custom dataset for water-body environments
Real-time image inference
High detection accuracy
Drone image compatibility
Scalable monitoring solution

🛠️ Technologies Used
Python
YOLOv8 (Ultralytics)
OpenCV
Google Colab
Roboflow
LabelImg
NumPy
Matplotlib

📂 Project Workflow
Data Collection
Image Annotation
Dataset Preparation
YOLOv8 Model Training
Model Validation
Object Detection
Result Visualization
Performance Evaluation

📊 Proposed System
Collect aerial images of water bodies.
Prepare and annotate the dataset.
Train a custom YOLOv8 object detection model.
Detect floating plastic waste in images or video streams.
Display bounding boxes with class labels.
Generate detection results for cleanup planning.

📁 Project Structure
Plastic-Waste-Detection/
│
├── dataset/
│   ├── images/
│   └── labels/
│
├── models/
│
├── runs/
│
├── notebooks/
│
├── results/
│
├── train.py
├── detect.py
├── requirements.txt
└── README.md

🚀 Installation
git clone https://github.com/Purva-Tagde/Plastic-Waste-Detection.git

cd Plastic-Waste-Detection

pip install -r requirements.txt

▶️ Training
yolo task=detect mode=train model=yolov8n.pt data=data.yaml epochs=100 imgsz=640

🔍 Detection
yolo task=detect mode=predict model=best.pt source=test_images/

📈 Expected Results
Accurate detection of floating plastic waste.
Faster monitoring compared to manual inspection.
Reduced operational costs.
Improved environmental surveillance.
Support for drone-based monitoring systems.

🔮 Future Scope
Live drone video detection.
Integration with GPS for location tracking.
Mobile application support.
Cloud-based monitoring dashboard.
Automatic waste reporting and analytics.
Expansion to underwater plastic detection.

📚 References
Ultralytics YOLOv8 Documentation
OpenCV Documentation
Roboflow
LabelImg
Open Images Dataset
Google Earth & Drone Imagery
UNEP Research
WWF Reports
