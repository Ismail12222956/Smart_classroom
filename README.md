# Student Engagement Analysis

This project implements a **Vision-Based Student Engagement Classification System** that detects whether a student is *Engaged* or *Not Engaged* using image data. It leverages **Convolutional Neural Networks (CNNs)** built with TensorFlow/Keras for automated engagement recognition.

---

## 🚀 Features

* Preprocesses image datasets by flattening and splitting into train/test sets
* Applies **data augmentation** for robust training
* Builds and trains a **CNN model** for binary classification
* Provides visualization of sample images and model performance
* Can be extended for real-time classroom monitoring applications

---

## 📂 Project Structure

* **Dataset Handling**: Organizes student engagement images into train/test folders
* **Data Augmentation**: Improves model generalization with transformations
* **Model**: CNN with multiple convolution, pooling, and dense layers
* **Training & Evaluation**: Trains on labeled data and validates performance
* **Visualization**: Plots images and model accuracy/loss

---

## ⚙️ Technologies Used

* Python 3
* TensorFlow / Keras
* NumPy, Matplotlib
* ImageDataGenerator for augmentation

---

## 🖥️ How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/yourusername/student-engagement-analysis.git
   cd student-engagement-analysis
   ```
2. Install required dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Place your dataset in the specified `train/` and `test/` directories.
4. Run the notebook

   ```bash
   jupyter notebook student_eng.ipynb
   ```

---

## 📊 Results

* The model successfully distinguishes between *Engaged* and *Not Engaged* students.
* Performance can be further improved with **larger datasets**, **transfer learning**, or **Vision Transformers (ViT)**.

---

## 🔮 Future Scope

* Integration with **real-time classroom systems**
* Storing engagement levels in a database for analytics
* Expanding beyond binary classification to detect multiple engagement levels

---

## ✨ Acknowledgements

This work is part of ongoing research on **AI-driven Smart Classroom Systems** aimed at improving learning outcomes through vision-based engagement tracking.
