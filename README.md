# 🧠 Alzheimer’s Disease Detection using Deep Learning (CNN)

An **Artificial Intelligence based medical imaging project** that detects **Alzheimer’s disease stages from MRI brain scans** using **Convolutional Neural Networks (CNN)**.

This project demonstrates how **Deep Learning can assist doctors in early diagnosis of neurological disorders** by automatically analyzing MRI images.

---

## 🚀 Project Highlights

- ✔ Deep Learning based MRI classification  
- ✔ Multi-class Alzheimer stage detection  
- ✔ CNN architecture with regularization  
- ✔ Model evaluation and visualization  

---

## 🧩 Problem Statement

Alzheimer’s disease is a **progressive brain disorder** that slowly destroys memory and thinking skills.

Early diagnosis is critical for treatment and patient care.

However:

- MRI scan analysis requires expert radiologists  
- Manual diagnosis can be time-consuming  
- Early-stage symptoms can be difficult to detect  

This project uses **AI-powered image classification** to automatically detect Alzheimer stages from MRI scans.

---

## 🧠 Deep Learning Approach

The model uses **Convolutional Neural Networks (CNN)** built with:

- TensorFlow  
- Keras  

CNN models automatically learn **spatial patterns from images** such as:

- Brain structure changes  
- Texture differences  
- Shape abnormalities  

---

## 📂 Project Structure
Alzheimer-CNN-Project
│
├── dataset/
│ ├── MildDemented
│ ├── ModerateDemented
│ ├── NonDemented
│ └── VeryMildDemented
│
├── notebooks/
│ └── ALZHEIMERS_PROJECT.ipynb
│
└── README.md

---

## 📊 Dataset

The dataset contains **MRI brain images categorized into four classes**.

| Class | Description |
|------|-------------|
| NonDemented | Healthy brain |
| VeryMildDemented | Early stage |
| MildDemented | Moderate stage |
| ModerateDemented | Advanced stage |

Images are **resized and normalized before training** the CNN model.

---

## ⚙️ Model Architecture

The CNN model includes:

- Convolution Layers  
- Batch Normalization  
- MaxPooling Layers  
- Dropout Layers  
- Dense Layers  
- Softmax Output Layer  

These layers help the model **extract meaningful features from MRI images**.

---

## 📈 Model Training

| Parameter | Value |
|-----------|------|
| Image Size | 128 × 128 |
| Epochs | 20 |
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |

The model learns **patterns from MRI scans corresponding to Alzheimer stages**.

---

## 📊 Results

The model produces:

- Training Accuracy  
- Validation Accuracy  
- Loss curves  
- MRI image predictions  

These results demonstrate the ability of **CNN models to detect patterns in medical images**.

---

## 🖥️ How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/yourusername/alzheimer-cnn-project.git
cd alzheimer-cnn-project

## 2️⃣ Install Dependencies

pip install tensorflow numpy pandas matplotlib scikit-learn pillow


pip install tensorflow numpy pandas matplotlib scikit-learn pillow
3️⃣ Run the Notebook
jupyter notebook

Open:

ALZHEIMERS_PROJECT.ipynb
💡 Future Improvements

Possible improvements:

Transfer Learning using ResNet or VGG16

Explainable AI using Grad-CAM

Larger MRI datasets

Cloud deployment

Integration with healthcare systems

🧑‍💻 Author

George Edayadil
