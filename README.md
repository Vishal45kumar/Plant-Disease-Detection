# Plant-Disease-Detection
# 🌿 Plant Disease Detection System
An AI-powered web application that detects plant diseases from leaf images using Deep Learning.

## 🚀 Features

* 🔍 Upload plant leaf images for detection
* 🤖 Deep Learning model (TensorFlow/Keras)
* 📊 Confidence score for predictions
* 🦠 Disease identification (38 classes)
* 🎨 Interactive UI using Streamlit

## 🧠 Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Streamlit

## 📂 Dataset

#Dataset link - https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
#This dataset is recreated using offline augmentation from the original dataset.This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.
#Train (70295 images)
#Valid (17572 image)
#Test (33 images)

## 🖥️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the app

```bash
streamlit run main.py
```

---

## 📸 Demo

Upload a plant leaf image and get:

* Disease prediction
* Confidence score

If you like this project, give it a ⭐ on GitHub!

