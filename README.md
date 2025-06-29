# 🧠 Brain Tumor Segmentation using YOLOv11 and SAM2

This project focuses on the detection and segmentation of brain tumors in MRI images using advanced deep learning models: **YOLOv11** for object detection and **SAM2 (Segment Anything Model)** for precise segmentation.

## 🚀 Project Overview

The goal is to build a complete pipeline that:
- Detects brain tumors using YOLOv11 (bounding boxes)
- Segments the detected tumor region using SAM2 (pixel-wise masks)
- Visualizes the outputs and saves results for analysis

This system helps automate brain tumor localization and enhances diagnostic capabilities in medical imaging.

## 📂 Dataset

- **Source**: [Roboflow - Tumor Detection Dataset](https://universe.roboflow.com/brain-tumor-detection-wsera/tumor-detection-ko5jp)
- **Format**: YOLOv11 (images + `.txt` annotations)
- **Classes**: 1 (Tumor)
- **Data Splits**: Train / Valid / Test

📊 Tools & Technologies
Python
Google Colab
Ultralytics YOLOv11
Segment Anything (Meta)
OpenCV, Matplotlib

🤝 Acknowledgements
Special thanks to:
Roboflow for providing the dataset
Ultralytics & Meta AI for the YOLO and SAM models
Internship mentor/team for guidance and review

