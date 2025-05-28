# Hydrophobicity Classification of Composite Insulators using TinyML

This project focuses on classifying the hydrophobicity levels of composite insulators (HC1 to HC7) using lightweight Convolutional Neural Networks (CNNs) optimized for TinyML deployment.

## 🔍 Overview

Composite insulators degrade over time due to environmental stress, and their surface hydrophobicity plays a key role in preventing electrical flashovers. This project uses computer vision and TinyML to automate the classification of insulator images based on hydrophobicity levels.

## 💡 Objectives

- Classify insulator surface images into 7 hydrophobicity classes (HC1–HC7)
- Use lightweight CNNs (e.g., MobileNetV2, EfficientNet-Lite)
- Apply transfer learning using **Edge Impulse**
- Optimize models with **knowledge distillation** for deployment on TinyML boards

## 🗂 Dataset

- ~40,000 images categorized into HC1–HC7
- Balanced classes (~500 images/class)
- 80% training and 20% testing split
- Images collected under varying environmental conditions

## ⚙️ Model Training

- Models trained and fine-tuned using **Edge Impulse**
- Transfer learning applied to pre-trained CNNs
- Performance evaluated based on accuracy, memory usage, and inference time

## 🔧 Optimization

- **Knowledge distillation** used to compress large models into efficient versions
- Goal: Achieve real-time, low-memory inference suitable for devices like:
  - Arduino Nicla Vision
  - Arduino nano

## 📊 Current Status

- ✅ Dataset preparation and preprocessing complete  
- ✅ Initial model training and evaluation done  
- 🔄 Ongoing: Model optimization for TinyML deployment  

## 🚀 Deployment (Coming Soon)

- Real-time inference on embedded boards
- Integration with drone or IoT platforms for field monitoring

## 📎 Tools & Technologies

- Edge Impulse
- Python
- TensorFlow / Keras
- CNN Architectures: MobileNetV2, EfficientNet-Lite
- Embedded platforms: Arduino Nicla Vision, ESP-EYE



---

*This project is part of an academic research initiative focused on intelligent condition monitoring of electrical components using TinyML.*

