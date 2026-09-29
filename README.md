# Pneumonia Detection Using CNN and Transfer Learning

## 📌 Project Description

This project detects pneumonia from chest X-ray images using deep learning. Four models—CNN, VGG16, VGG19, and ResNet50—are trained to classify X-ray images as **NORMAL** or **PNEUMONIA**.

## 🎯 Objectives

- Detect pneumonia from chest X-ray images.
- Train and compare different deep learning models.
- Evaluate models using multiple performance metrics.
- Predict the class of a new X-ray image.

## 🤖 Models Used

- CNN
- VGG16
- VGG19
- ResNet50

VGG16, VGG19, and ResNet50 use **transfer learning with ImageNet weights**.

## 📂 Dataset

The dataset contains chest X-ray images divided into:

- NORMAL
- PNEUMONIA

The dataset is organized into:

```text
train/
├── NORMAL/
└── PNEUMONIA/

val/
├── NORMAL/
└── PNEUMONIA/

test/
├── NORMAL/
└── PNEUMONIA/
```

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Project Workflow

```text
Dataset
   ↓
Image Preprocessing
   ↓
CNN ────────┐
VGG16 ──────┤
VGG19 ──────┤ → Model Comparison
ResNet50 ───┘
   ↓
Performance Evaluation
   ↓
Single Image Prediction
```

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## ▶️ How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook.
3. Install the required libraries.
4. Place the dataset in the specified folder.
5. Run the notebook cells in order.
6. Train the four models.
7. Compare their performance.
8. Use the single-image prediction section to test an X-ray.

## 📁 Project Structure

```text
Pneumonia-Detection/
│
├── nndl1.ipynb
├── model_comparison.csv
├── .gitignore
└── README.md
```

## 🔮 Future Scope

- Use a larger and more diverse dataset.
- Apply fine-tuning to improve transfer-learning models.
- Develop a web-based interface for image prediction.
- Improve model generalization and validation.

 
