# DeepLearning-Diabetes-Prediction
Deep learning project using Keras to predict diabetes from medical data (Pima Indians Dataset).

# 🧠 Diabetes Prediction using Deep Learning

## 📌 Overview
This project applies a **Deep Learning model (Keras Sequential Neural Network)** to predict the likelihood of diabetes in patients using the **Pima Indians Diabetes Dataset**.  
The dataset includes key health indicators such as glucose levels, BMI, age, blood pressure, and insulin levels.  

The model is trained, saved, and later reloaded for predictions, demonstrating an **end-to-end machine learning workflow**.

---

## 📂 Dataset
**Pima Indians Diabetes Dataset**  
- Features:
  1. Number of pregnancies  
  2. Plasma glucose concentration  
  3. Diastolic blood pressure (mm Hg)  
  4. Triceps skinfold thickness (mm)  
  5. 2-hour serum insulin (mu U/ml)  
  6. Body Mass Index (BMI)  
  7. Diabetes pedigree function  
  8. Age (years)  
- **Target:** Diabetes diagnosis (0 = No, 1 = Yes)  

---

## ⚙️ Model Architecture
- Input layer: 8 features  
- Hidden Layer 1: Dense(12), ReLU activation  
- Hidden Layer 2: Dense(8), ReLU activation  
- Output Layer: Dense(1), Sigmoid activation  

**Loss Function:** Binary Crossentropy  
**Optimizer:** Adam  
**Metrics:** Accuracy  

---

## 🚀 Workflow
1. **Data Loading** (`pima-indians-diabetes.csv`)  
2. **Model Training** (`train.py`)  
   - Compile and fit neural network  
   - Evaluate accuracy  
   - Save trained model (`model.json`, `model.h5`)  
3. **Model Testing** (`test.py`)  
   - Reload saved model  
   - Predict on dataset samples  
   - Print predictions vs actual labels  

---

## 📊 Results
- Achieved **~75–80% accuracy** on the dataset (depending on epochs and hyperparameters).  
- Predictions demonstrate correct classification of diabetic vs non-diabetic patients.  

---

## 🛠️ Tech Stack
- Python  
- Numpy  
- Keras (TensorFlow backend)  

---

## 📈 Impact
This project demonstrates **what**: predicting diabetes using deep learning,  
**how**: by training a feedforward neural network on health indicators,  
and **effect**: supporting medical diagnosis and preventive healthcare.  

---

## 👤 Author
Ruvtika – M.Tech Civil Engineering (Hydrology & Water Resources), IIT Kanpur 
