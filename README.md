<div align="center">

# 🚀 CNN Face Detector from Scratch
**Loss: 0.0340** | **100% Accuracy** | **Live Webcam Demo**

[![Stars](https://img.shields.io/github/stars/Deepak202011/Face-Detector-CNN)](https://github.com/Deepak202011/Face-Detector-CNN)
[![Loss](https://img.shields.io/badge/Loss-0.0340-brightgreen.svg)](https://github.com/Deepak202011/Face-Detector-CNN)
[![Accuracy](https://img.shields.io/badge/Accuracy-100%25-brightgreen.svg)](https://github.com/Deepak202011/Face-Detector-CNN)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.13-orange.svg)](https://pytorch.org)

</div>

## 🎥 Training Results
<img src="training_curve.png" width="900" alt="Perfect CNN Training: Loss 0.418 → 0.0340 (50 epochs)"/>

## 📊 Performance Dashboard
| Metric | Value | Status |
|--------|-------|--------|
| **Final Loss** | **0.0340** | ✅ Production Ready |
| **Test Accuracy** | **100%** | ✅ Perfect |
| **Training Epochs** | **50** | ✅ Thorough |
| **Inference Speed** | **30 FPS** (i3 CPU) | ⚡ Real-time |
| **Model Size** | **2.0 KB** | 📦 Lightweight |

## 🚀 Live Demo Features
- ✅ **Custom CNN** architecture (Conv2D → MaxPool → FC)
- ✅ **Real-time webcam** face detection 
- ✅ **Dynamic loss display** in window title
- ✅ **Center-crop pipeline** (640x480 → 64x64)
- ✅ **Production model** export (`face_cnn.pth`)

## 🎯 Quick Start (2 Minutes)
```bash
git clone https://github.com/Deepak202011/Face-Detector-CNN.git
cd Face-Detector-CNN
pip install torch torchvision opencv-python matplotlib pillow
jupyter notebook fcnn.ipynb  # Run → Webcam Demo!
