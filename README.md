# Comparative Analysis of YOLOv8 and DETR on TUM RGB-D Dataset

## 📌 Project Overview
This project presents a comparative study of two state-of-the-art object detection models — **YOLOv8** and **DETR (DEtection TRansformer)** — evaluated on the **TUM RGB-D indoor dataset**.

The objective is to analyze their performance with respect to:
- Detection speed
- Accuracy and robustness
- Occlusion handling
- Suitability for real-time and semantic SLAM-based applications

This work is particularly motivated by applications in **robotics, indoor scene understanding, and semantic SLAM**.

---

## 🚀 Models Used
- **YOLOv8 (Ultralytics)**  
  - CNN-based, single-stage detector  
  - Optimized for real-time detection  
  - Lightweight and deployment-friendly  

- **DETR (Facebook AI)**  
  - Transformer-based end-to-end detector  
  - Global reasoning using attention mechanism  
  - Strong in cluttered and complex scenes  

---

## 📂 Dataset
- **TUM RGB-D Dataset**
- Indoor scenes captured using Microsoft Kinect
- Widely used benchmark dataset for SLAM and robotic vision research

Website: http://vision.in.tum.de/data/datasets/rgbd-dataset

---

## ⚙️ Methodology
1. Extraction of RGB frames from TUM RGB-D sequences  
2. Preprocessing and resizing  
3. Inference using YOLOv8 and DETR on identical frames  
4. Visualization of bounding boxes  
5. Speed comparison and qualitative evaluation  

---

## 📊 Evaluation Metrics
- Frames Per Second (FPS)
- Bounding Box Accuracy (IoU-based observation)
- Occlusion handling
- Scene understanding quality
- Visualization clarity


