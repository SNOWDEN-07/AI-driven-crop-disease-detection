 AI-Based Crop Disease Detection

An AI-powered web application that detects crop diseases from leaf images using deep learning. Designed to assist farmers and agricultural professionals in identifying diseases early and suggesting remedies to improve yield and crop health.


 Project Overview

This system uses Convolutional Neural Networks (CNN) trained on labeled datasets of plant leaf images to identify crop diseases with high accuracy. The model is deployed via a web interface that allows users to upload an image of a diseased leaf and receive instant diagnosis and treatment recommendations.

 Features

-  Image-based disease classification
-  Supports multiple crop types (e.g., Tomato, Potato, Corn)
-  Suggests possible remedies
-  User-friendly web interface
-  Trained using TensorFlow/Keras on PlantVillage dataset

 Folder Structure

crop-disease-detector/
│
├── 📁 model/ # Trained model files (.h5, .pkl)
├── 📁 dataset/ # Training and validation image dataset
├── 📁 webapp/
│ ├── app.py # Flask or Streamlit backend
│ ├── templates/ # HTML files (if Flask)
│ ├── static/ # CSS, JS, and image files
│
├──  utils/ # Helper functions (e.g., image processing)
├── requirements.txt # Dependencies
├── README.md # You're reading it!
└──  train_model.ipynb # Notebook to train model



 Tech Stack

- Python 3.9+
- TensorFlow / Keras
- OpenCV
- NumPy
Project Report Download Link- https://drive.google.com/file/d/1-z1-rC5lHNT6-UH-sxeCakIIr90VeIe9/view?usp=drive_link
