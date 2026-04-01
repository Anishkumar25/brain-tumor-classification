# 🧠 Brain Tumor Classification using EfficientNet-B2

Deep learning model for **MRI brain tumor classification** into four categories using **EfficientNet-B2 transfer learning**.

This project is part of an ongoing **research study on automated brain tumor detection using deep learning**.
Additional models, experiments, and the research paper will be added in future updates.

---

## 📌 Project Overview

Early detection of brain tumors from MRI scans can significantly assist medical diagnosis.
This project uses a **Convolutional Neural Network (CNN)** based on **EfficientNet-B2** to classify MRI images into four tumor categories.

The model learns visual patterns from MRI scans and predicts the tumor type automatically.

---

## 🎯 Classification Classes

The model classifies MRI scans into the following categories:

1. Glioma Tumor
2. Meningioma Tumor
3. Pituitary Tumor
4. No Tumor

---

## 🧠 Model Architecture

Model Used: **EfficientNet-B2**

EfficientNet is a deep learning architecture that scales network **depth, width, and resolution** in a balanced way, leading to strong performance with fewer parameters.

Transfer learning was applied using a pretrained EfficientNet-B2 backbone.

---

## 📊 Model Performance

Training Accuracy: **93.75%**
Validation Accuracy: **94.31%**

Classification Report:

| Class   | Precision | Recall | F1 Score |
| ------- | --------- | ------ | -------- |
| Class 0 | 0.99      | 0.97   | 0.98     |
| Class 1 | 1.00      | 1.00   | 1.00     |
| Class 2 | 0.97      | 0.97   | 0.97     |
| Class 3 | 0.98      | 1.00   | 0.99     |

Overall Accuracy: **98%**

Total Test Samples: **6365**

---

## 📂 Repository Structure

```
BrainTumor_EfficientNetB2
│
├── efficientnet_b2_training.ipynb
├── README.md
│
└── results
    ├── confusion_matrix.png
    └── training_plot.png
```

---

## ⚙️ Technologies Used

Python
TensorFlow / Keras
EfficientNet
NumPy
Matplotlib
Scikit-learn

---

## 🚀 How to Run the Project

Clone the repository

```
git clone https://github.com/yourusername/brain-tumor-classification-efficientnetb2.git
```

Navigate to the project folder

```
cd brain-tumor-classification-efficientnetb2
```

Install required libraries

```

Run the training notebook

```
efficientnet_b2_training.ipynb
```

---

## 🔬 Research Work (In Progress)

This repository is part of an ongoing research project.

Future updates will include:

• Comparison with other EfficientNet variants
• Model performance analysis
• Grad-CAM visualization for tumor localization
• Additional deep learning architectures
• Published research paper

---

## 📌 Future Improvements

• Multi-model comparison
• Explainable AI visualization
• Model optimization
• Deployment for clinical support systems

---

## 👨‍💻 Author

P.AnishKumar

Student Research Project
Deep Learning for Medical Image Analysis

---

## ⭐ Acknowledgement

This project explores the use of deep learning for **automated brain tumor classification** and aims to contribute to research in **AI-assisted medical diagnosis**.
