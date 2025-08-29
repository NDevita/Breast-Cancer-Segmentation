# 🩺 Breast Cancer Segmentation Using Breast Ultrasound Images

## 📌 Overview
This project aims to **perform breast cancer segmentation** on **Ultrasound (USG) images**.  
The dataset is taken from **Kaggle**, which contains breast images classified into three categories:  
- **Normal**  
- **Benign** (non-cancerous)  
- **Malignant** (cancerous)  

---

## 📂 Dataset
- **Source**: [Breast Ultrasound Images (Kaggle)](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)  
- **Description**: The dataset consists of a collection of breast ultrasound images with labels for each image.  

**Dataset Structure:**
- `images/`: Folder containing ultrasound images  
- `masks/`: Folder containing segmentation masks of tumors  
- `label`: Category (Normal, Benign, Malignant)  

---

## ⚙️ Dependencies
This project uses **Python** with the following main libraries:

- `numpy`  
- `pandas`  
- `opencv-python`  
- `matplotlib`  
- `seaborn`  
- `tensorflow` / `keras`  
- `scikit-learn`  
