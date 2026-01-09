# Web Project

A full-stack web application Learning System with a deployed frontend and backend API.

## 🚀 Live Links

### Frontend
🔗 https://webproject-blush-chi.vercel.app/

### Backend API
🔗 https://webproject-1-kssl.onrender.com  
📌 Base URL: https://webproject-1-kssl.onrender.com/api  
🛠 Deployed on: Render

## 🧰 Tech Stack
- Frontend: HTML, CSS, JavaScript (or React – update if needed)
- Backend: Node.js, Express
- Deployment: Vercel (Frontend), Render (Backend)

## 📌 Description
This project demonstrates a complete web application workflow, including frontend UI, backend API, and live deployment. It focuses on building, connecting, and deploying a full-stack application.



# Chatx Final Version

This is a computer networks project that implements a peer-to-peer communication platform, allowing direct communication between peers over a network.

## 📌 Project Type
- Computer Networks / Networking Project
- Peer-to-Peer (P2P) Communication

## 📂 Project Files
All source files required to run the project are included in the repository.

➡️ **Important:**  
Please refer to the `Runme.txt` file for detailed instructions on how to compile, configure, and run the project.




# Extended Multi-Class Geographical Classification

## Desert, Mountain, and Lake Detection from Satellite Images Using Deep Feature Fusion

This repository contains the research work titled **“Extended Classification of Geographical Features: Desert, Mountain, and Lake Detection from Satellite Images Using Deep Feature Fusion”**.

The study proposes a deep learning–based framework for multi-class land-cover classification using satellite imagery. It extends prior binary classification approaches by introducing **lake detection** and a **deep feature fusion strategy** to improve performance in a more challenging three-class scenario.

---

## 📄 Abstract
Satellite imagery plays a key role in environmental monitoring and land-cover analysis. This work presents an enhanced deep learning approach for automatically classifying satellite images into **desert**, **mountain**, and **lake** categories. The framework employs pre-trained **DenseNet models** for feature extraction, followed by feature reduction and **serial feature fusion**. The fused feature vector is then classified using SoftMax and traditional machine-learning classifiers.

Experimental results demonstrate that the proposed **FFV-SM (Fused Feature Vector with SoftMax)** approach achieves up to **99.25% accuracy**, outperforming individual DenseNet models and previously reported two-class systems.

---

## 🧠 Methodology Overview
- Image resizing to 224 × 224 × 3
- Deep feature extraction using DenseNet121, DenseNet169, and DenseNet201
- Feature reduction (50%) using dropout-based selection
- Serial feature fusion of DenseNet121 and DenseNet201
- Classification using:
  - SoftMax
  - Decision Tree
  - Random Forest
- Three-fold cross-validation for robustness
- Grad-CAM for model interpretability

---

## 📊 Dataset
- Source: **Kaggle SkyView Dataset**
- Classes:
  - Desert
  - Mountain
  - Lake
- Total images: **3,600**
  - 1,200 images per class
- Data augmentation:
  - Rotation
  - Flipping
  - Zoom
  - Brightness and contrast adjustments

---

## 🧪 Experimental Setup
- Python 3.10
- TensorFlow 2.8
- NVIDIA RTX 3070 GPU (8 GB VRAM)
- Optimizer: SGD
- Learning rate: 1e-4
- Batch size: 8
- Epochs: 40

---

## 🏆 Results
- **Best accuracy:** 99.25% (FFV-SM)
- Random Forest fusion accuracy: 98.70%
- Stable performance across all three classes
- Grad-CAM visualizations confirm attention on meaningful landscape features

---

## 🔍 Key Contributions
- Extension from binary to **multi-class** geographical classification
- Introduction of **lake detection**
- Deep feature fusion using multiple DenseNet models
- High accuracy with strong generalization
- Improved robustness through cross-validation and interpretability analysis

---

## 📚 Keywords
Deep Learning, Satellite Imagery, DenseNet, Feature Fusion, Multi-Class Classification, Lake Detection, Environmental Monitoring

---

## 📌 Citation
If you use this work, please cite the corresponding paper.

---

## 👤 Authors
- Zahraa Msheik  
- Lynn Hamieh  
- Michael Geha  

---

## 📎 Paper
The full paper is available in this repository as a PDF.

