# 🦷 AI-Powered Detection of Periapical Lesions on IOPA Radiographs

## 📌 Overview

This project presents an end-to-end deep learning pipeline for the automated detection of **periapical lesions and dental caries** using **intraoral periapical (IOPA) radiographs**.
The goal is to assist clinicians by improving diagnostic accuracy and reducing human variability.

---

## 🚀 Features

* Image preprocessing (resize, normalization, CLAHE)
* Data annotation using bounding boxes
* CNN-based classification (EfficientNet-B0 / ResNet-50)
* YOLOv8-based object detection for lesion localization
* Performance evaluation using accuracy, precision, recall, AUC, and mAP
* Visualization with confusion matrix and detection outputs

---

## 🧠 Tech Stack

* Python
* TensorFlow / PyTorch
* OpenCV
* Ultralytics YOLOv8
* Google Colab / GPU Cluster

---

## 📂 Project Structure

```
├── data/                # Dataset (not included)
├── annotations/         # Label files (YOLO / JSON)
├── preprocessing/       # Image preprocessing scripts
├── models/
│   ├── classification/  # CNN models
│   └── detection/       # YOLOv8 models
├── training/            # Training pipelines
├── evaluation/          # Metrics & analysis
├── results/             # Outputs & visualizations
└── README.md
```

---

## ⚙️ Workflow

1. Data collection & anonymization
2. Annotation (lesions & caries)
3. Preprocessing (resize, normalization, CLAHE)
4. Model training (classification + detection)
5. Evaluation & comparison with expert analysis

---

## 📊 Evaluation Metrics

* Accuracy
* Sensitivity & Specificity
* Precision & Recall
* F1-Score
* ROC-AUC
* mAP (for detection)

---

## ⚠️ Dataset Disclaimer

The dataset used in this project consists of **anonymized dental radiographs** and is **not publicly available** due to ethical and privacy considerations.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Contributors

* Prathamesh Khaire
* Krrish Mahajan
* Bhoomi Tiwary 
* Harsh Patil

---

## 💡 Future Scope

* Extend model to OPG and CBCT imaging
* Improve generalization with larger datasets
* Real-time clinical integration

---

## ⭐ Acknowledgment

Developed as part of an academic research project in collaboration with dental and AI/ML department (BVDU).
