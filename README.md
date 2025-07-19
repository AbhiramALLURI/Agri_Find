# 🌿 AgriFind

**AI-Powered Plant Disease Detection for Smarter Farming**

## 📌 Overview

**AgriFind** is a machine learning project developed to assist farmers with early and accurate identification of plant diseases. By leveraging computer vision, the system enables real-time detection of diseases from leaf images — helping to reduce crop loss and improve agricultural productivity.

The solution is deployed using **Streamlit**, providing a simple and user-friendly web interface without the need for complex frontend development.

## 🚀 Features

- 📷 **Leaf Image Classification**
  - Upload an image of a plant leaf and get instant disease prediction.

- 🧠 **High-Accuracy CNN Model**
  - Achieves ~95% accuracy using deep learning on 40,000+ training images.

- 🛠 **Streamlit Deployment**
  - Lightweight, browser-based interface ideal for farmers and agricultural workers.

- 🔁 **Robust Preprocessing**
  - Data augmentation and cleaning improve the model’s generalization.

## 🛠️ Tech Stack

| Component        | Technology                    |
|------------------|-------------------------------|
| **Language**      | Python                        |
| **Libraries**     | TensorFlow / Keras, NumPy, OpenCV |
| **Model Type**    | Convolutional Neural Network (CNN) |
| **Deployment**    | Streamlit                     |
| **Data**          | 40,000+ labeled leaf images   |

## 🧠 Model Architecture

- Input: Preprocessed leaf images (resized, normalized)
- Layers: Convolution → MaxPooling → Flatten → Dense → Softmax
- Output: Predicted class label (disease type)
- Trained with categorical cross-entropy and Adam optimizer

## 📈 Performance

- ✅ **Accuracy**: ~95%
- 📊 **Dataset**: 40,000+ labeled images of healthy and diseased leaves
- 🔁 **Augmentation**: Rotation, flipping, brightness/contrast tweaks

