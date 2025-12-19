# Image Reconstruction and Super-Resolution using Invertible Neural Networks (INN)

This project implements an Invertible Convolutional Neural Network (INN) for image reconstruction and super-resolution. 
The model is trained to perform both forward (compression) and inverse (reconstruction) mappings, enabling high-quality image recovery.

---

## 🚀 Features
- Invertible neural network architecture for bidirectional image mapping
- Forward pass for latent representation learning
- Inverse pass for image reconstruction and super-resolution
- Quantitative evaluation using PSNR and SSIM
- Experiments conducted on the CIFAR-10 dataset

---

## 🧠 Model Architecture
- Invertible Convolutional Blocks
- Coupling layers with exact reversibility
- Shared weights for forward and inverse transformations

---

## 📊 Evaluation Metrics
- **PSNR (Peak Signal-to-Noise Ratio)**
- **SSIM (Structural Similarity Index Measure)**

These metrics are used to compare reconstruction quality against traditional interpolation methods.

---

## 🛠️ Tech Stack
- Python
- TensorFlow
- NumPy
- Matplotlib

---

## 📂 Dataset
- CIFAR-10 (https://www.cs.toronto.edu/~kriz/cifar.html)

---

## ▶️ How to Run
```bash
git clone https://github.com/sujan-duhh/invertible-image-super-resolution.git
cd invertible-image-super-resolution
pip install -r requirements.txt
python train.py

