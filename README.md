# mask-detector-CNN

##🛡️ Face Mask Detector - CNN Based

This project is a Convolutional Neural Network (CNN)-based face mask detection system that can classify whether a person is wearing a mask or not in real-time using a webcam or image input.

Built and trained entirely using **Google Colab**, this model leverages `TensorFlow/Keras` for model development and `OpenCV` for live detection.

---


Images: ![image](https://github.com/user-attachments/assets/8eed304a-131b-464a-9aca-118bb74171a7)
![imageno](https://github.com/user-attachments/assets/5a617f51-7d4f-4c2c-889f-f900d41f3f20)

---

## 📊 Dataset

The dataset used consists of images of people with and without face masks, sourced from publicly available datasets like:
- https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset

---

## 🧠 Model Architecture

- **Convolutional Layers** (with ReLU activation)
- **MaxPooling Layers**
- **Dropout** for regularization
- **Flatten + Dense Layers**
- Final layer with **sigmoid** (binary classification)

---

## 🚀 How to Use

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/mask-detector-cnn.git
cd mask-detector-cnn
