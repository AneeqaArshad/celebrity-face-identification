# 🎭 Celebrity Face Identification — Deep Learning (CNN)

A complete end-to-end **celebrity face identification system** built using Convolutional Neural Networks (CNNs), full image augmentation, preprocessing pipeline, model training, evaluation, and real-world inference.

This project demonstrates **practical deep learning skills**, including data handling, augmentation, model design, hyperparameter tuning, and image-based predictions — packaged as a production-ready workflow.

---

## 🚀 Features

### ✔️ **1. Dataset Handling**

* Automatic path loading
* Image preprocessing
* Train/validation split
* Normalization & resizing pipeline

### ✔️ **2. Data Augmentation**

Used to improve generalization and reduce overfitting:

* Horizontal flip
* Rotation
* Zoom
* Brightness adjustment
* Shear transformation
* Width/height shifts

### ✔️ **3. Convolutional Neural Network (CNN)**

A custom-built CNN architecture including:

* Conv2D layers
* MaxPooling
* Batch Normalization
* Dropout layers to avoid overfitting
* Fully connected dense classifier

### ✔️ **4. Training & Evaluation**

* Model training with accuracy/loss curves
* Validation metrics
* Model checkpointing
* Final accuracy evaluation

### ✔️ **5. Real-World Inference Pipeline**

* Load any face image
* Preprocess automatically
* Model predicts the celebrity label
* Ready for integration into apps or APIs

---

## 🧱 Project Structure

```
📁 celebrity-face-identification
│── 📄 README.md
│── 📄 LICENSE
│── 📄 .gitignore
│── 📄 celebrity_face_detection.ipynb
│── 📄 requirements.txt (optional)
│── 📁 saved_model/ (optional)
│── 📁 dataset/ (optional)
```

---

## 📦 Requirements

If you want to run the notebook locally, install:

```bash
pip install tensorflow keras numpy opencv-python matplotlib scikit-learn
```

---

## ▶️ How to Run

1. Clone the repo

   ```bash
   git clone https://github.com/AneeqaArshad/celebrity-face-identification
   ```
2. Open the Jupyter Notebook
3. Run all cells
4. Upload any image to test prediction

---

## 📊 Model Performance

* High classification accuracy
* Generalizes well after augmentation
* Performs reliably on real-world images

---

## 📌 Notes

This project is fully designed, implemented, and tested end-to-end by **Aneeqa Arshad**.
For professional use, the model can be extended into:

* A Flask API
* A web dashboard
* A mobile app predictor

---

## 📝 License

This project uses the **MIT License** — free for personal and commercial use.

---

## 🌟 Author

**Aniqa Arshad**
Deep Learning • Computer Vision • Python • Applied AI

---

If you like this project, please ⭐ star the repository!
