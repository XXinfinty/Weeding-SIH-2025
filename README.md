# 🌱 WEEDING-SIH-2026 — Autonomous Weeding Robot

🚜 **SIH 2026 — AgriTech Innovation**
An AI-powered autonomous robot that detects and removes weeds in real-time using computer vision and edge AI.

---

## 🎯 Problem Statement

Manual weed removal increases farming cost, time, and labor dependency.
Farmers in India spend significant resources on chemical herbicides and manual weeding.

This project builds an **Autonomous Weeding Robot** capable of:

* Detecting weeds in real-time
* Performing precision spraying
* Running fully on edge hardware (Jetson Nano)

---

## 🚀 Key Features

✅ Real-time Weed Detection using **YOLOv8**
✅ Edge AI deployment on **NVIDIA Jetson Nano**
✅ Precision Spraying Mechanism
✅ Soil Moisture + Pressure Sensor Integration
✅ Autonomous Field Monitoring System
✅ Lightweight ONNX inference model

---

## 🛠 Tech Stack

### 🤖 AI / Software

* Python
* YOLOv8 (Ultralytics)
* ONNX Runtime
* OpenCV
* PyTorch (Training Phase)

### ⚙️ Hardware

* NVIDIA Jetson Nano (Edge AI Processor)
* CSI Camera Module
* Soil Moisture Sensor
* Pressure Sensor
* Relay Modules
* Precision Sprayer System
* Battery Powered Mobile Robot Platform

---

## 📂 Dataset

Model trained using:

👉 **MH-16 Weed Dataset**

Dataset is NOT included in the repository due to size limits.

You can obtain it from:

```
https://www.kaggle.com/datasets/sayalis069/mh-weed16
```

---

## 🧠 Model Details

| Parameter     | Value               |
| ------------- | ------------------- |
| Model Type    | YOLOv8              |
| Export Format | ONNX                |
| Edge Device   | Jetson Nano         |
| Inference     | Real-time Detection |

The ONNX model is stored using **Git LFS** for efficient version control.

---

## 🏗 System Architecture

### Pipeline:

1️⃣ Capture Field Images (Jetson Nano Camera)
2️⃣ Run YOLOv8 ONNX Inference
3️⃣ Detect Weed Coordinates
4️⃣ Validate Sensor Data
5️⃣ Trigger Precision Spray
6️⃣ Log Data & System Status


---

## 🔌 Hardware Implementation

The robot integrates multiple sensors and control modules:

* Jetson Nano processes image streams
* Camera captures crop rows
* Soil moisture sensor monitors field condition
* Pressure sensor ensures spray system stability
* Relay module controls sprayer activation

---
## 👨‍💻 Contributors

Team Neaooo — Smart India Hackathon 2026

---

## 📜 License

This project is licensed under the MIT License — see LICENSE file for details.



If you like this project, consider giving it a ⭐ on GitHub!

