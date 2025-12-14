# 🫁 PneumoScan AI: Pneumonia Detection System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview
**PneumoScan AI** is a Deep Learning application designed to assist in the detection of Pneumonia from Chest X-Ray images. The system utilizes **Transfer Learning** with the **VGG16** architecture to classify images as either "Normal" or "Pneumonia".

The project consists of two main parts:
1.  **Training Module:** Model training pipeline using TensorFlow/Keras.
2.  **Deployment App:** An interactive web dashboard built with Streamlit.

## ⚠️ Important: Model File Access
Due to GitHub's file size limits, the trained model file (`model_pneumonia_vgg16.h5`) is hosted externally. 

**To run this application locally, you must download the model:**
[[**Download Model Here**]](https://drive.google.com/file/d/1yVRtws8oPglN_h3JKpBooY-sd98xJ884/view?usp=sharing)


## 🚀 Features
* **Transfer Learning:** Uses pre-trained VGG16 weights for feature extraction.
* **Real-time Analysis:** Instant prediction on uploaded X-Ray images.
* **Confidence Score:** Displays the probability percentage of the diagnosis.
* **Visualization:** Interactive probability charts using Streamlit.

## 🧠 Model Architecture
* **Base Model:** VGG16 (ImageNet weights, top layers excluded).
* **Custom Head:** Flatten Layer -> Dense (Relu) -> Dropout -> Output (Softmax/Sigmoid).
* **Optimizer:** Adam.
* **Loss Function:** Binary Crossentropy.

## 🤝 Credits & Acknowledgements
* **Base Concept:** This project's training pipeline was adapted and enhanced from [GeeksforGeeks](https://www.geeksforgeeks.org/deep-learning/pneumonia-detection-using-deep-learning/)
* **Dataset:** [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
* **Frameworks:** TensorFlow, Keras, Streamlit.

## ⚖️ Disclaimer
This tool is for educational purposes only. It is not a substitute for professional medical diagnosis. Always consult a certified radiologist or doctor for medical advice.
