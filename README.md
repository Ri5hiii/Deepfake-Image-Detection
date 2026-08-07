🛡️ AI-Based DeepFake Image Detection System

Detect AI-generated images using EfficientNet-B4 and Grad-CAM Explainable AI

An advanced Deep Learning-based image forensic system that classifies images as Real or AI-Generated using EfficientNet-B4. The project also integrates Grad-CAM to visualize the regions influencing the model's decision, making the predictions more interpretable and trustworthy. The complete system is deployed through a Streamlit web application.

📌 Overview

The rapid growth of AI image generation models such as DALL·E, Midjourney, Stable Diffusion, Adobe Firefly, and GLIDE has increased the need for reliable image authenticity verification. This project provides a practical solution for detecting AI-generated images using transfer learning and explainable AI techniques.

✨ Features
🔍 Detects whether an image is Real or AI-Generated
🧠 EfficientNet-B4 based Deep Learning model
🔥 Grad-CAM heatmap visualization
🎯 Face Region Risk Analysis (6 Facial Zones)
📊 Confidence Score & Probability Distribution
🌐 Interactive Streamlit Web Application
⚡ GPU & CPU compatible inference
🏗️ System Architecture
Input Image
      │
      ▼
Image Preprocessing
      │
      ▼
EfficientNet-B4 Classifier
      │
      ├────────► Real / Fake Prediction
      │
      ▼
Grad-CAM Heatmap Generation
      │
      ▼
Face Region Risk Analysis
      │
      ▼
Streamlit Dashboard
🧠 Model
Architecture: EfficientNet-B4
Framework: PyTorch
Transfer Learning
Binary Classification
Grad-CAM Explainability
AdamW Optimizer
Cosine Annealing Scheduler
Mixed Precision (AMP) Training
📂 Dataset
Real Images
MS COCO 2017
Fake Images (SynthBuster)
DALL·E 2
DALL·E 3
Midjourney V5
Stable Diffusion 1.3
Stable Diffusion 1.4
Stable Diffusion 2.0
Stable Diffusion XL
Adobe Firefly
GLIDE
Dataset Statistics
Category	Images
Real Images	10,000
Fake Images	10,000
Total Images	20,000

Training Split:

75% Training
15% Validation
10% Testing
🛠️ Technologies Used
Category	Technology
Language	Python
Deep Learning	PyTorch
Model	EfficientNet-B4
Explainability	Grad-CAM
Web Framework	Streamlit
Computer Vision	OpenCV
Image Processing	Pillow
Data Handling	NumPy
Visualization	Matplotlib
Evaluation	Scikit-learn
📊 Project Workflow
Upload Image
Image Preprocessing
DeepFake Detection
Confidence Score Calculation
Grad-CAM Heatmap Generation
Face Region Risk Analysis
Display Final Result
📸 Application Preview

The Streamlit application provides:

Image Upload
Prediction Result
Real vs Fake Probability
Grad-CAM Heatmap
Face Region Analysis
Model Statistics
Interactive Dashboard
📁 Project Structure
DeepFake-Detection/
│
├── app.py
├── train.py
├── predict.py
├── gradcam.py
├── dataset/
├── models/
├── utils/
├── requirements.txt
├── best_model.pth
├── README.md
└── assets/
🚀 Installation
git clone https://github.com/Rishiii/deepfake-image-detection.git

cd deepfake-image-detection    

pip install -r requirements.txt

streamlit run app.py
📈 Future Improvements
Video DeepFake Detection
Vision Transformer (ViT) Integration
Mobile Application Deployment
Multi-class AI Generator Identification
Cloud Deployment
Real-time API Support
👨‍💻 Team Members
Rishikesh Barkade
Sakshi Baghel
Sangeeta Dhurve
Guide

Mrs. Megha Kuliha
Associate Professor
Department of Information Technology
SGSITS, Indore

📜 License

This project is developed for academic and research purposes as a Minor Project under the Department of Information Technology, SGSITS, Indore.
