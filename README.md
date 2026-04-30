# Oral-Cancer-Detection-using-AI-ML
An AI-based system for oral cancer detection using medical images, designed with a multi-task CNN architecture for classification, confidence estimation, and visual explainability.
## 📌 Overview
This project focuses on detecting oral cancer from medical images using deep learning. 
Unlike traditional models, this system emphasizes both prediction accuracy and interpretability, 
which is critical in healthcare applications.

## 🚀 Features
- Image-based cancer classification using CNN (EfficientNet)
- Multi-task learning (classification + confidence estimation)
- Transfer learning for improved performance on limited data
- Data augmentation for better generalization
- Grad-CAM visualization for explainable AI

## 🧠 Model Architecture
- Base Model: EfficientNet (pretrained)
- Custom Layers for classification and confidence output
- Fine-tuning applied for domain-specific learning

## 📊 Results
- Achieved moderate accuracy on medical image dataset
- Improved reliability through confidence estimation
- Visual explanations highlight important regions in images

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Matplotlib
- Google Colab

## 📁 Dataset
- Oral cancer image dataset (mention source if public)
- Preprocessed using resizing, normalization, and augmentation

## 📌 Future Work
- Improve accuracy using advanced fine-tuning
- Add deployment (web/app interface)
- Extend to multi-modal learning (image + clinical data)

## 🤝 Contributions
Open to suggestions and improvements!
