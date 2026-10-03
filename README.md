# 🚀 Spacecraft Image Segmentation
 
## 📌 Project Overview
 
This project focuses on semantic image segmentation of spacecraft components using deep learning techniques.
 
The goal is to build a computer vision model capable of accurately identifying and segmenting different spacecraft parts, including the main body, solar panels, and antennas, using both real and synthetic satellite imagery.
 
---
 
## 🎯 Project Objectives
 
- Perform semantic image segmentation
- Train a deep learning model on spacecraft imagery
- Segment spacecraft components with pixel-level accuracy
- Evaluate segmentation quality using mIoU
- Compare predicted masks with ground-truth masks
 
---
 
## 📊 Dataset
 
The dataset contains **3,116 spacecraft images** with segmentation masks.
 
### Mask Resolution
 
- 1280 × 720 pixels
 
### Segmentation Classes
 
🟩 Green — Spacecraft Body
 
🟥 Red — Solar Panels
 
🟦 Blue — Antennas
 
### Data Split
 
- Training Set:
- 403 precise masks
- 2,114 coarse masks
 
- Validation Set:
- 600 precise masks
 
---
 
## 🧠 Deep Learning Approach
 
The project uses a semantic segmentation architecture designed for multi-class segmentation tasks.
 
The model learns to assign each image pixel to one of the predefined spacecraft component classes.
 
---
 
## 📏 Evaluation Metrics
 
### Mean Intersection over Union (mIoU)
 
Primary metric used to evaluate segmentation quality.
 
Project target:
 
```text
mIoU > 0.70
```
 
### Training Loss
 
Training and validation loss values were monitored during model optimization.
 
---
 
## 🔍 Project Workflow
 
### 1. Data Preparation
 
- Dataset loading
- Mask preprocessing
- Image augmentation
 
### 2. Model Training
 
- Multi-class segmentation training
- Loss optimization
- Validation monitoring
 
### 3. Model Evaluation
 
- mIoU calculation
- Prediction quality assessment
 
### 4. Result Visualization
 
- Original image visualization
- Predicted mask visualization
- Ground-truth mask comparison
 
---
 
## 📈 Results
 
The model achieved:
 
### ✅ Mean IoU = 0.9312
 
Training observations:
 
- Stable convergence during training
- Continuous reduction in loss values
- High-quality segmentation masks
- Accurate detection of spacecraft components
 
---
 
## 🛠 Technologies
 
- Python
- PyTorch
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook
 
---
 
## 🚀 Installation
 
Clone the repository:
 
```bash
git clone https://github.com/Alex1988Den/Spacecraft-Image-Segmentation.git
cd Spacecraft-Image-Segmentation
```
 
Install dependencies:
 
```bash
pip install -r requirements.txt
```
 
Launch Jupyter Notebook:
 
```bash
jupyter notebook
```
 
Open:
 
```text
Spacecraft_Image_Segmentation.ipynb
```
 
and run all cells.
 
---
 
## 💡 Applications
 
- Satellite Image Analysis
- Aerospace Computer Vision
- Spacecraft Component Detection
- Remote Sensing
- Industrial Image Segmentation
 
---
 
## 👨‍💻 Author
 
Developed by **Aleksandr Denissov**
 
📧 Email: aleksandr.denissov@brave.ee
 
---
 
⭐ If you find this project useful, feel free to leave a star on GitHub.
