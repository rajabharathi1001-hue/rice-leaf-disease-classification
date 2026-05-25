# Rice Leaf Disease Classification using CNN

## Project Overview
This project focuses on detecting and classifying rice leaf diseases using **Convolutional Neural Networks (CNN)** and Deep Learning techniques. The model analyzes rice leaf images and predicts disease categories to support early detection and agricultural monitoring.

The project uses **Python, TensorFlow, Keras, NumPy, and Matplotlib** for image preprocessing, model training, evaluation, and prediction.

---

## Problem Statement
Rice crops are highly vulnerable to diseases that affect productivity and crop quality. Manual identification of rice leaf diseases can be time-consuming and prone to human error.

The objective of this project is to:

- Detect rice leaf diseases from image data
- Classify different disease categories accurately
- Support faster agricultural disease diagnosis
- Improve early disease detection using Deep Learning

---

## Technologies Used

### Programming & Machine Learning
- Python
- Deep Learning
- Computer Vision
- CNN (Convolutional Neural Network)

### Python Libraries
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Dataset Information
The dataset contains rice leaf images categorized into different disease classes.

### Disease Classes
- Bacterial Leaf Blight
- Brown Spot
- Leaf Smut

The model was trained using labeled rice leaf disease images for classification.

---

## Project Workflow

### 1. Data Collection & Image Loading
- Imported rice leaf disease image dataset
- Loaded images for training and validation
- Organized disease categories

### 2. Image Preprocessing
- Image loading using TensorFlow/Keras
- Image resizing and normalization
- Training and validation dataset preparation
- Batch processing for CNN training

### 3. Deep Learning Model Development
Built a **Convolutional Neural Network (CNN)** for rice disease classification.

Model Architecture Includes:
- Convolutional Layers
- Pooling Layers
- Flatten Layer
- Dense Layers
- Activation Functions

### 4. Model Training
- Trained CNN model on rice leaf dataset
- Monitored training and validation accuracy
- Evaluated model performance over multiple epochs

### 5. Model Evaluation
Performance analysis using:

- Training Accuracy
- Validation Accuracy
- Loss Curve Analysis
- Prediction Confidence Scores

### 6. Disease Prediction
- Predicted disease type from rice leaf images
- Displayed prediction confidence scores
- Compared actual vs predicted labels

---

## Project Results
- Successfully classified rice leaf diseases using CNN
- Achieved high validation accuracy
- Generated confidence-based disease predictions
- Visualized model performance trends

---

## Project Structure

```text
rice-leaf-disease-classification/
│── dataset/
│   └── Leaves/
│
│── notebook/
│   └── rice_leaf_disease_classification.ipynb
│
│── screenshots/
│   ├── sample_rice_leaf_images.png
│   ├── cnn_model_training.png
│   ├── training_validation_accuracy_loss.png
│   └── rice_leaf_prediction_results.png
│
│── requirements.txt
│── README.md
```

---

## Screenshots
The project includes:

- Sample rice leaf disease images
- CNN training process
- Training & validation accuracy/loss curves
- Actual vs predicted disease classification

---

## Future Improvements
- Improve model accuracy using Transfer Learning
- Hyperparameter tuning
- Real-time disease detection system
- Web deployment using Streamlit

---

## Author
**Raja Bharathi R**

Data Analyst | Aspiring Data Scientist | Machine Learning Enthusiast
