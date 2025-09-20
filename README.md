# CIFAR-10: Data Augmentation, HOG Features, kNN & SVM

## 📌 Project Overview
This project demonstrates classical machine learning on the **CIFAR-10 dataset**.  
Instead of deep CNNs, we extract **handcrafted features (HOG)** from images and train **kNN** and **SVM** classifiers.  

The pipeline includes:
- Loading and splitting CIFAR-10 into **train / validation / test sets**
- **Visualizing** original and augmented images with class labels
- **Normalization** of pixel values (scaling and standardizing per channel)
- **Data augmentation** (random crop, horizontal flip, color jitter)
- **Feature extraction** using **HOG descriptors**
- Training and evaluating **kNN** and **Linear SVM** classifiers
- Visualizing **HOG feature maps** of augmented samples

---

## ⚙️ Setup

### 1. Install Dependencies
```bash
pip install torch torchvision scikit-image scikit-learn matplotlib numpy

### 2. Create a folder of cifar10data

### 3. CIFAR-10 downloads from:
https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz





