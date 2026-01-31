🧘 YogAI — AI-Powered Yoga Pose Detection & Evaluation System

Capstone Project | Computer Vision | Deep Learning
📜 Patent Published: AI-Powered Yoga Pose Detection & Evaluation System
Application No.: 202541122968 (Indian Patent Office)

📌 Overview

YogAI is an end-to-end real-time yoga pose detection and evaluation system that leverages computer vision and deep learning to classify yoga postures and provide corrective feedback from live camera input.

The system introduces a novel hybrid deep learning architecture, combining VGG16 convolutional feature extraction with PoseNet skeletal keypoint estimation, significantly improving robustness across diverse lighting conditions, orientations, and body variations.

🚀 Key Contributions & Novelty

✔ Hybrid VGG16 + PoseNet architecture for enhanced spatial & skeletal representation
✔ Real-time inference pipeline using live webcam streams
✔ Patent-published system design for pose evaluation & feedback
✔ ~12% accuracy improvement via training & hyperparameter optimization
✔ Device-agnostic web deployment using Flask & React
✔ No specialized hardware required

🧠 System Architecture
Live Camera Input
        ↓
PoseNet (Keypoint Detection)
        ↓
VGG16 (Early Convolutional Feature Fusion)
        ↓
Hybrid Deep Learning Model
        ↓
Pose Classification
        ↓
Corrective Feedback (Web UI)

🛠 Tech Stack
Category	Technologies
Programming	Python
Deep Learning	TensorFlow, Keras
Computer Vision	OpenCV, PoseNet
Backend	Flask
Frontend	React
Data Processing	NumPy, Pandas
Visualization	Matplotlib
📊 Dataset

~2,000+ yoga posture images

Multiple poses, body types, angles, and lighting conditions

Manually curated and split into training & testing sets

📁 Dataset Access (Google Drive):
👉 https://drive.google.com/drive/folders/1h-bbWRkLnz6NGz_EST0UeIpreXIUWSOX

⚠️ Dataset not included in GitHub due to size constraints.

📈 Model Training & Optimization

Transfer learning with VGG16

PoseNet for skeletal keypoint extraction

Data augmentation for generalization

Hyperparameter tuning:

Learning rate

Batch size

Optimizer selection

Achieved ~12% performance improvement over baseline CNN models

🧪 Notebooks
Notebook	Description
Final_Model.ipynb	Final training & evaluation pipeline
Final_Posenet.ipynb	PoseNet keypoint extraction
Proposed_VGG16.ipynb	Hybrid VGG16-PoseNet architecture
🌐 Web Application

Flask backend for inference

React frontend for real-time visualization

Live camera input

Pose classification & feedback display

Fully device-agnostic

⚙️ Installation & Setup
git clone https://github.com/<your-username>/YogAI.git
cd YogAI
pip install -r requirements.txt

▶️ Running the Application
python src/inference.py


Then open browser at:

http://localhost:5000

📜 Patent Information

AI-Powered Yoga Pose Detection & Evaluation System
Indian Patent Office
Application No.: 202541122968

📌 Future Enhancements

Mobile application support

Real-time pose correction scoring

Multi-pose session tracking

Transformer-based pose modeling

Cloud deployment (AWS / GCP)

👤 Author

Atharva H.
MS Data Science
Capstone Project — 2025

📄 License

This project is licensed under the MIT License.