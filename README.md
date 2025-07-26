# 🌿 Plant Disease Detection Web App

A deep learning–based web app that detects plant diseases from leaf images using a trained TensorFlow model, all wrapped in a simple and interactive Streamlit interface.

---

## 🚀 Features

- 📷 Upload plant leaf images to get disease predictions
- ✅ Supports 38 plant disease classes
- 🌐 Built with Streamlit for a clean and fast UI
- ⚡ Fast predictions using a pre-trained model

---

## 🖼️ Demo

![Home Page](home_page.jpeg)

---

## 🔍 How It Works

1. **Upload** a leaf image using the web app.
2. The image is preprocessed and passed to the trained model.
3. The app displays the predicted disease class.

---

## 📦 Dataset

- Contains ~87,000 images of healthy and diseased crop leaves.
- Images are categorized into 38 classes.
- Split into `train/`, `valid/`, and `test/` directories.
- ⚠️ The dataset is **only needed for training**. You **don't need it** to run the prediction app.

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/plant-disease-detection.git
   cd plant-disease-detection
