# 🌿 Plant Disease Detection Web App

This project leverages Convolutional Neural Networks (CNNs) for high-accuracy image classification to detect plant diseases. Going beyond basic machine learning, it utilizes deep learning techniques with TensorFlow/Keras to learn spatial hierarchies in images, creating a scalable, real-world deep learning solution. The application is wrapped in a user-friendly Streamlit interface, capable of making accurate predictions on unseen plant diseases.

---

## 🚀 Features

* **📷 Upload plant leaf images** to get disease predictions.
* **✅ Supports 38 plant disease classes**, covering a wide range of common plant ailments.
* **🌐 Built with Streamlit** for a clean, fast, and interactive user interface.
* **⚡ Fast predictions** using a pre-trained CNN model.

---

## 🖼️ Demo

*(You can add an image or GIF of your running app here for a visual demo. Replace this text with the image link once uploaded to your repo.)*
`![Demo Image](home_page.jpeg)`

---

## 🔍 How It Works

1.  **Upload a leaf image** using the intuitive web application.
2.  The image is **preprocessed** to match the model's input requirements.
3.  The preprocessed image is then **passed to the trained CNN model** for inference.
4.  The app **displays the predicted disease class** to the user.

---

## 📦 Dataset

The project utilizes a comprehensive dataset containing **~87,000 images of healthy and diseased crop leaves**, categorized into **38 distinct classes**. This dataset is structured into `train/`, `valid/`, and `test/` directories for robust model development.

**⚠️ Note:** The dataset is only required for training the model. You do **not** need to download or include it to run the prediction application.

---

## 🛠️ Installation

To get the application up and running locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/plant-disease-detection.git](https://github.com/your-username/plant-disease-detection.git)
    cd plant-disease-detection
    ```
    *(Remember to replace `your-username` with your actual GitHub username.)*

2.  **Install dependencies:**
    ```bash
    pip install -r requirement.txt
    ```

3.  **Run the app locally:**
    ```bash
    streamlit run main.py
    ```

---

## 📂 Project Structure
├── main.py                   # Main Streamlit application file
├── requirement.txt           # Python dependencies for the project
├── home_page.jpeg            # UI image used in the application (e.g., for the homepage)
├── Train_plant_disease.ipynb # Jupyter Notebook for training the CNN model
├── Test_plant_disease.ipynb  # Jupyter Notebook for evaluating/testing the trained model
├── training_hist.json        # Logs of the model's training history
├── trained_model.h5          # The pre-trained Convolutional Neural Network model file
├── Dataset/                  # Full dataset for training purpose

---

## 📊 Accuracy

The CNN model developed for this project achieves **high accuracy (90%+)** on validation data. It's important to note that performance may vary depending on the specific dataset distribution and the quality of the input images.

---

## 📚 Tech Stack & Libraries

This project is built using a robust set of technologies and libraries, chosen for their efficiency in deep learning workflows, rapid development capabilities, and accessible deployment:

* **Python** — The core programming language.
* **TensorFlow & Keras** — For building, training, and managing the deep Convolutional Neural Network models.
* **Streamlit** — Utilized to construct an interactive, user-friendly, and simple web interface.
* **NumPy, Pandas** — Essential for efficient data handling and preprocessing.
* **Matplotlib, Seaborn** — Employed for effective data visualization and insights during development.
* **scikit-learn** — Used for various model evaluation metrics and utilities.

---

## 💡 Why This Isn't a Basic Project

This project stands out from basic machine learning classification models by employing a **CNN architecture** capable of capturing complex spatial patterns in leaf imagery. It involves working with a **large, real-world dataset**, demanding preprocessing, and encompasses the entire deep learning pipeline: **model training, saving, loading, and deployment** via Streamlit. These comprehensive elements collectively position it as a strong intermediate-level deep learning project.

---

## 🚀 Future Improvements

* Add support for **mobile upload or camera integration** for on-the-go predictions.
* **Improve UI/UX** (User Interface/User Experience) for even better usability and visual appeal.

---

## 🙏 Acknowledgments

* **Dataset Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).
* **Streamlit** for providing an excellent framework for building intuitive machine learning web applications.

---

## 📅 License

This project is licensed under the **MIT License** 
