# End-to-End Computer Vision Food Classifier 🍎🥦🥕

This repository contains the implementation of a computer vision system designed to classify food items into three main categories: fruits, vegetables, and others.

## 🚀 Key Achievement
**Accomplished** the deployment of an end-to-end classification system, **as measured by** a 98% validation accuracy on 56,000+ images and a successful live showcase at EXPOESCOM, **by training** an EfficientNetB0 model and developing an interactive Tkinter GUI with real-time OpenCV integration.

## ✨ Main Features
* **Multiclass Classification:** Automated grouping into three main categories (Fruits, Vegetables, Others) from dozens of individual subcategories (e.g., apples, broccoli, beans).
* **Transfer Learning & Fine-Tuning:** Utilization of the pre-trained **EfficientNetB0** model with ImageNet weights, freezing initial layers and training the final ones to extract and classify food-specific features.
* **Massive Data Processing:** Cleaning, preprocessing, and resizing images to 224x224 pixels for a massive dataset, resulting in 45,122 training samples and 11,309 validation samples.
* **Real-Time Interface & Inference:** Robust system architecture ready to be integrated with a Tkinter graphical interface to feed live webcam predictions using OpenCV.

## 🛠️ Technologies Used
* **Language:** Python
* **Deep Learning & Computer Vision:** TensorFlow, Keras, EfficientNetB0, OpenCV
* **Data Processing & Analysis:** Pandas, NumPy, Scikit-learn, PIL
* **Visualization:** Matplotlib, Seaborn

## 📦 Project Structure
* `Prueba_rednuronal_frutas_verduras_otros.ipynb`: Main notebook containing the complete workflow: directory exploration, data preprocessing, array structuring (.npz), and model training.
* `GUI/`: (Optional) Scripts for running the interactive graphical user interface.
* `models/`: Directory to store the best model weights (e.g., `mejor_modelo_finetune_frutas_verduras.h5`) saved via the `ModelCheckpoint` callback.

## ⚙️ Usage and Training
The experimentation and training pipeline is executed directly within the Notebook. Key steps include:
1. **Data Loading and Splitting:** Iterating through images, processing them, assigning numerical labels, and performing a balanced 80/20 train-validation split.
2.
