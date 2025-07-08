# Hand-Written Digit Recognition using CNN (LeNet-5 & AlexNet) 🧠✍️

This project focuses on classifying hand-written digits (0–9) using deep learning models. We have implemented and compared **LeNet-5** and **AlexNet** architectures on the **MNIST dataset** using TensorFlow and Keras.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Highlights

- 📚 **Dataset**: MNIST (70,000 grayscale images of digits 0–9)
- 🧠 **Models Used**: LeNet-5, AlexNet
- 📈 **Evaluation**: Accuracy, Loss
- 📊 **Libraries**: TensorFlow, Keras, NumPy, Matplotlib

---

## 📂 Dataset Details

- **Source**: Loaded via `tensorflow.keras.datasets`
- **Training Samples**: 60,000 images
- **Testing Samples**: 10,000 images
- **Image Dimensions**: 28x28 pixels, grayscale

---

## 🧠 Model Architectures

### 🔹 LeNet-5
- Conv (6 filters, 5×5) → AvgPool  
- Conv (16 filters, 5×5) → AvgPool  
- FC → FC → Softmax

### 🔹 AlexNet (Modified for MNIST)
- Conv layers with ReLU and MaxPooling  
- Fully Connected layers with Dropout  
- Softmax Output for 10 classes

---


## 🧪 Libraries Used
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 🙋‍♂️ Author
**Sammi Kumar**  
GitHub: [@Sammishahi](https://github.com/Sammishahi)
---

## 💡 Future Improvements
- Add confusion matrix and classification report  
- Try deeper models like VGG16/ResNet  
 
