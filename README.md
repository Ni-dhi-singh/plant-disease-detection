# 🌿 Plant Disease Detection

This is a web application that detects plant diseases using a trained deep learning model. It allows users to upload an image of a plant leaf, and the app predicts the type of disease (if any) using a `.h5` model.

---


---

## 🚀 Features

- Upload an image of a plant leaf.
- Predicts the disease using a trained model.
- Provides the class name and confidence score.
- Simple and clean UI (optional via Streamlit or Flask).

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Ni-dhi-singh/plant-disease-detection.git
cd plant-disease-detection/app


---

## 📊 Dataset

The model was trained on the [PlantVillage Dataset](https://drive.google.com/uc?export=download&id=YOUR_FILE_ID), a labeled image dataset of healthy and diseased plant leaves.

- 📁 Format: ZIP archive containing image folders per class
- 🧾 Classes: Apple scab, Tomato blight, Grape black rot, etc.
- 🗂 Structure: `/class_name/image.jpg`
- 📦 Size: ~1.2 GB (after unzip)

Please download and extract this dataset to use for retraining or testing.


🤖 Trained Model

- 🔗 [Download Model (.h5)](https://drive.google.com/uc?export=download&id=YOUR_MODEL_FILE_ID)
- 📄 Format: Keras `.h5` model
- 🧠 Used for: Inference in `main.py` via TensorFlow

---

⚠️ Make sure to place the model inside the `app/trained_model/` folder after download for the app to work correctly.
