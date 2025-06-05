# Plant Disease Classification

# 🌿 Plant Disease Classification

Plant Disease Classification is a deep learning-based project that identifies and classifies diseases in plants from leaf images. This system helps farmers and agricultural experts diagnose plant health quickly and accurately, enabling timely intervention and improved crop management.

---

## 🚀 Project Overview

This project leverages convolutional neural networks (CNN) to classify plant leaf images into multiple disease categories. It automates the detection of common plant diseases, reducing reliance on manual inspection and expert knowledge.

---

## ✨ Features

- **Accurate Disease Detection** from leaf images using deep learning.
- **Multi-class Classification** for various plant diseases.
- **Preprocessing** includes image resizing, normalization, and augmentation.
- **Model Training** with popular CNN architectures.
- **Evaluation Metrics** such as accuracy, precision, recall, and F1-score.
- **User-friendly Interface** (optional) to upload leaf images and get disease prediction.

---

## 📂 Repository Contents

| Folder/File           | Description                                   |
|----------------------|-----------------------------------------------|
| `dataset/`           | Collection of plant leaf images for training and testing |
| `models/`            | Saved trained CNN models                       |
| `notebooks/`         | Jupyter notebooks for data exploration, model training, and evaluation |
| `src/`               | Source code for preprocessing, training, and inference |
| `requirements.txt`   | List of Python dependencies                     |
| `README.md`          | Project documentation                           |

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy, Pandas  
- Matplotlib, Seaborn (for visualization)  
- Jupyter Notebook  

---

## 🎯 Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/AkashBhagatGH/PlantDiseaseClassification.git
   cd PlantDiseaseClassification
   
2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3.Install dependencies
pip install -r requirements.txt

4.Run notebooks or scripts
jupyter notebook

