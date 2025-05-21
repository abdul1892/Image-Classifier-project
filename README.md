## 🧠 Project Overview

This project is a binary image classifier that detects human emotions—specifically **Happy** and **Sad**—from facial images using a Convolutional Neural Network (CNN). The model is trained on a labeled dataset of facial images and learns to classify expressions into one of the two categories: `Happy` or `Sad`.

This system can be used for emotion-based human-computer interaction, mood tracking, or mental health monitoring applications.

---

## 📌 Key Features

- Classifies images into two categories: **Happy** 😊 and **Sad** 😢
- Built with **TensorFlow/Keras**
- Uses **CNN architecture** for high accuracy
- Can be easily retrained with custom datasets
- Simple CLI for training and prediction

---

## 💻 Technologies Used

| Tool/Library   | Purpose                          |
|----------------|----------------------------------|
| Python 3.8+     | Programming language             |
| TensorFlow/Keras | Deep learning framework         |
| NumPy          | Numerical computations            |
| Matplotlib     | Data visualization                |
| Scikit-learn   | Model evaluation (accuracy, F1)   |


---

## 🧾 Dataset Description

The dataset consists of two folders:
- `data/happy/`: Contains images of people with happy expressions.
- `data/sad/`: Contains images of people with sad expressions.

Each image is a face cropped to focus on emotional features. All images are resized to a fixed dimension before training.

---





