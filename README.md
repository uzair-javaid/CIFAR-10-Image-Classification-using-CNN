# 🧠 CIFAR-10 Image Classification using CNN

This project builds a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset** into 10 categories, including airplanes, cars, birds, cats, dogs, and more.
It demonstrates basic deep-learning concepts such as convolution, pooling, activation functions, and dropout for regularization.

---

## 📂 Dataset

* **Images:** 60,000 color images (32×32 pixels)
* **Classes (10):** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

> The dataset is automatically loaded using TensorFlow — no manual download required.

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 🚀 Project Workflow

1. **Load & preprocess** CIFAR-10 dataset
2. **Build CNN model** using Keras Sequential API
3. **Train the model** on training data
4. **Evaluate accuracy** on test data
5. **Visualize** accuracy and loss curves
6. **Save & load model** for predictions

---

## 🧩 Model Architecture

```
Conv2D(32, (3,3), activation='relu')
MaxPooling2D(2,2)
Conv2D(64, (3,3), activation='relu')
MaxPooling2D(2,2)
Flatten()
Dense(128, activation='relu')
Dropout(0.3)
Dense(10, activation='softmax')
```

---

## 📈 Results

* **Training Accuracy:** ~80–85% (after 10 epochs)
* **Test Accuracy:** ~75–80% (depending on training time)

Sample output:

```
📊 Test Accuracy: 78.42%
💾 Model saved as 'cifar10_cnn_model.h5'
```

---

## 🔍 Prediction Example

Random test image prediction output:

```
🎯 Predicted: Dog
```

Displays the image with predicted label.

---

## 💾 Saved Model

The trained model is saved as:

```
cifar10_cnn_model.h5
```

You can reload it anytime for further testing or fine-tuning.

---

## 🧑‍💻 Author

**Uzair Javaid**
Final-year B.Tech (Computer Science) student passionate about AI, Deep Learning.


---
