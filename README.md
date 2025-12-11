# AI-helmet-detection
# 🏍️ Motorcycle Helmet Detection using YOLOv8

## 🚀 Overview

This project implements an **object detection model using YOLOv8 (Ultralytics)** to detect motorcyclists and classify whether they are wearing helmets. The aim is to enhance road safety compliance monitoring.

---

## 📌 Problem Statement

Ensuring road safety compliance requires automated systems to detect if motorcyclists are wearing helmets. Manual monitoring is inefficient and prone to errors.

---

## 💡 Solution Approach

1. **Dataset Collection:**  
   - Utilised **Roboflow** to obtain and prepare a custom dataset for motorcycle helmet detection.

2. **Model Selection & Training:**  
   - Implemented YOLOv8 nano model (`yolov8n.pt`) using **Ultralytics library**.  
   - Trained for **20 epochs** with an image size of **640x640** for optimal speed and accuracy balance.

3. **Evaluation:**  
   - Validated the model on test images to assess detection accuracy and visual output.

4. **Inference:**  
   - Performed detection on test images using Google Colab and visualised results with bounding boxes using OpenCV.

---

## ⚙️ Tech Stack

- **Python**
- **YOLOv8 (Ultralytics)**
- **PyTorch**
- **Roboflow**
- **Google Colab**
- **OpenCV**

---


