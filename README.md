# 🖊️ Handwritten Digit Recognition using SVM

This project uses **Support Vector Machines (SVM)** to recognize handwritten digits from the **scikit-learn digits dataset**. It includes training, testing, and visualization of predictions for digit classification.

---

## 📌 Project Overview

- 📚 Dataset: `sklearn.datasets.load_digits` (8x8 grayscale images of digits 0–9)
- 🤖 Model: Support Vector Classifier (SVC) with a linear kernel
- 📈 Goal: Predict the correct digit from image pixel data
- 🖼️ Output: Visual display of predicted digits with their images

---

## 🚀 Technologies Used

- Python 🐍
- Scikit-learn (`sklearn`)
- Matplotlib for visualization
- NumPy

---

## 🧠 How It Works

1. **Load the digits dataset**
2. **Flatten the 8x8 image data** into 1D vectors
3. **Split** data into training and testing sets
4. **Train** the SVM classifier using `SVC(kernel='linear')`
5. **Predict** the digits on test data
6. **Evaluate** model using accuracy and classification report
7. **Display** 8 test images with their predicted labels

---

## 📂 Project Structure

```plaintext
├── digit_recognition_svm.py   # Main Python script
├── README.md                  # Project documentation 
