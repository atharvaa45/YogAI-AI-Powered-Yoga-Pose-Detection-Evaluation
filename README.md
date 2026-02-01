# 🧘 YogAI — AI-Powered Yoga Pose Detection & Evaluation System

**Capstone Project | Computer Vision | Deep Learning**  

📜 **Patent Published**: *AI-Powered Yoga Pose Detection & Evaluation System*  
**Application No.: 202541122968** (Indian Patent Office)

---

## 📌 Project Overview

**YogAI** is an end-to-end **real-time yoga pose detection and evaluation system** that leverages **computer vision and deep learning** to accurately classify yoga postures and provide intelligent feedback using live camera input.

The project introduces a **novel hybrid deep learning architecture** that fuses **PoseNet-based skeletal keypoint estimation** with **VGG16 convolutional feature extraction**, enabling robust pose recognition across different body orientations, lighting conditions, and camera viewpoints.

This system was designed, implemented, optimized, and deployed as a **capstone-level production-ready application**, and the methodology has been **successfully published as a patent**.

---

## 🎯 Objectives

- Detect human body keypoints in real time using live camera input  
- Accurately classify yoga poses using deep learning  
- Improve pose recognition robustness under real-world conditions  
- Provide a scalable, device-agnostic web-based solution  
- Introduce architectural novelty beyond traditional CNN-based approaches  

---

## 🧠 Key Contributions & Novelty

- Hybrid **VGG16 + PoseNet** deep learning architecture  
- Early convolutional feature fusion for enhanced spatial representation  
- Real-time end-to-end inference pipeline  
- ~12% improvement in accuracy through training optimization  
- Patent-published system design  
- Full-stack deployment using Flask and React  
- No specialized hardware required  

---

## 🏗️ System Architecture

Live Camera Input

↓

PoseNet (Skeletal Keypoint Detection)

↓
VGG16 (Convolutional Feature Extraction)

↓
Hybrid Deep Learning Model

↓
Yoga Pose Classification

↓

Corrective Feedback (Web Interface)


---

## 🛠️ Tech Stack

### Programming & Frameworks
- Python  
- TensorFlow / Keras  

### Computer Vision
- OpenCV  
- PoseNet  

### Backend
- Flask  
- Flask-CORS  

### Frontend
- React  

### Data & Utilities
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📊 Dataset

- Over **2,000 yoga posture images**
- Multiple yoga poses
- Diverse body types, angles, and lighting conditions
- Split into training and testing datasets

📁 **Dataset Link (Google Drive)**  
https://drive.google.com/drive/folders/1h-bbWRkLnz6NGz_EST0UeIpreXIUWSOX

> ⚠️ Dataset is not included in this repository due to GitHub size limitations.

---

## 📈 Model Training & Optimization

- Transfer learning using **VGG16**
- PoseNet-based skeletal keypoint extraction
- Data preprocessing and normalization
- Hyperparameter tuning:
  - Learning rate
  - Batch size
  - Optimizer selection
- Achieved approximately **12% improvement** over baseline CNN models

---

## 📓 Jupyter Notebooks

| Notebook Name | Description |
|--------------|-------------|
| `Final_Model.ipynb` | End-to-end training and evaluation pipeline |
| `Final_Posenet.ipynb` | PoseNet-based keypoint extraction |
| `Proposed_VGG16.ipynb` | Proposed hybrid VGG16–PoseNet architecture |

---

## 🌐 Web Application

### Backend
- Flask-based inference server
- Handles real-time prediction requests

### Frontend
- React-based user interface
- Live camera feed
- Real-time pose classification and feedback

### Features
- Device-agnostic execution  
- Real-time inference  
- Lightweight deployment  

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

    git clone https://github.com/<your-username>/YogAI.git
    cd YogAI

### 2. Install Dependencies

    pip install -r requirements.txt

---

## ▶️ Running the Application

    python src/inference.py

Open your browser at:

    http://localhost:5000

---

## 📜 Patent Information

**Title:** AI-Powered Yoga Pose Detection & Evaluation System  
**Patent Office:** Indian Patent Office  
**Application Number:** 202541122968  
**Status:** Published

---

## 🔮 Future Enhancements

- Mobile application deployment  
- Real-time posture correction scoring  
- Multi-pose session tracking and analytics  
- Transformer-based pose modeling  
- Cloud deployment (AWS / GCP)

---

## 👤 Author

**Atharva H.**  
MS in Data Science  
Capstone Project — 2025

---

## 📄 License

This project is licensed under the **MIT License**.
