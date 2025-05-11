# Facial Emotion Detection 🎭🧠

This project implements a facial emotion detection system using the [FER2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013). It leverages **transfer learning** with a fine-tuned **VGG19** model and integrates **Explainable AI (XAI)** using **LIME** for visualizing important regions in facial expressions.

## 🔍 Overview

- ✅ Dataset: FER2013 (7 emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral)
- 🧠 Model: VGG19 pretrained on ImageNet, fine-tuned for emotion classification
- 📊 Evaluation: Accuracy, confusion matrix, and sample predictions
- 🔍 Explainability: LIME and SHAP visualization for model interpretability

## 🧪 Key Features

- **Data Preprocessing**: Normalization, resizing, and train/val splitting
- **Transfer Learning**: VGG19 base with custom dense layers
- **Fine-tuning**: Selective unfreezing of layers to improve emotion recognition
