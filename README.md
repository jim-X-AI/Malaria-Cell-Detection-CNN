# 🦠 Malaria Cell Detection with CNN

A deep learning project for detecting malaria-infected cell images using a Convolutional Neural Network (CNN). The model classifies cell images as either **infected** or **uninfected**, and achieves over **95% accuracy** on the test set.


---

## 🧠 Model Architecture

The CNN architecture used:

- Conv2D (32 filters, 3x3, ReLU)
- MaxPooling2D
- Conv2D (64 filters, 3x3, ReLU)
- Conv2D (124 filters, 3x3, ReLU)
- Flatten
- Dense (64 units, ReLU)
- Dense (32 units, ReLU)
- Dense (1 unit, Sigmoid)

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- Scikit-learn
- NumPy

---

## 📊 Training & Evaluation

- Image Size: 60x60 pixels
- Batch Size: 128
- Optimizers: SGD and Adam (compared)
- Early Stopping used to prevent overfitting
- Achieved 95%+ accuracy on test set

---

## 📈 Results

- Final Validation Accuracy: **~95%**
- Binary Classification Report (on test set) is generated
- Model training/validation loss curves plotted
- Model saved with `pickle` for reuse

---

## 🔍 Example Cell Image

![Example Cell Image](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Malaria_plasmodium.jpg/220px-Malaria_plasmodium.jpg)

---

## 📦 How to Run

1. Clone the repo:

```bash
git clone https://github.com/jim-X-AI/Malaria-Cell-Detection-CNN.git
cd Malaria-Cell-Detection-CNN


