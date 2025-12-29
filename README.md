# 🖼️ Image Caption Generator using CNN & LSTM

An **Image Caption Generator** is a Deep Learning–based application that automatically generates meaningful and grammatically correct textual descriptions for images. This project combines **Computer Vision** and **Natural Language Processing (NLP)** using **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory (LSTM)** models.

---

## 📌 Project Overview

With the rapid growth of digital images on social media and the web, understanding image content automatically has become essential. This project aims to generate captions in **simple English** for any given image.

The system works by:
- Extracting visual features from images using **CNN**
- Generating descriptive sentences using **LSTM**
- Producing captions similar to human-written descriptions

---

## 🚀 Features

- Automatic image caption generation  
- CNN-based image feature extraction  
- LSTM-based sequential text generation  
- Trained on the Flickr8k dataset  
- Produces meaningful and natural captions  
- Useful for assistive technologies  

---

## 🧠 Technologies Used

- Python  
- TensorFlow / Keras  
- Convolutional Neural Network (CNN)  
- Long Short-Term Memory (LSTM)  
- NumPy  
- Matplotlib  

---

## 🏗️ System Architecture

The architecture consists of two main components:

### 1️⃣ Encoder – CNN  
Extracts important visual features from the input image using a pre-trained CNN model (VGG16).

### 2️⃣ Decoder – LSTM  
Generates captions sequentially based on extracted image features.

