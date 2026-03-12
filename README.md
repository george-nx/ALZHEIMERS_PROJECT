🧠 Alzheimer’s Disease Detection using Deep Learning (CNN)

An Artificial Intelligence based medical imaging project that detects Alzheimer’s disease stages from MRI brain scans using Convolutional Neural Networks (CNN).

This project demonstrates how Deep Learning can assist doctors in early diagnosis of neurological disorders by automatically analyzing MRI images.

🚀 Project Highlights

✔ Deep Learning based MRI classification
✔ Multi-class Alzheimer stage detection
✔ CNN architecture with regularization
✔ Model evaluation and visualization
✔ Optional web prediction app using Streamlit

🧩 Problem Statement

Alzheimer’s disease is a progressive brain disorder that slowly destroys memory and thinking skills.

Early diagnosis is critical for treatment and patient care.

However:

MRI scan analysis requires expert radiologists

Manual diagnosis can be time-consuming

Early-stage symptoms can be difficult to detect

This project uses AI-powered image classification to automatically detect Alzheimer stages from MRI scans.

🧠 Deep Learning Approach

The model uses Convolutional Neural Networks (CNN) built with:

TensorFlow

Keras

CNN models automatically learn spatial patterns from images such as:

Brain structure changes

Texture differences

Shape abnormalities

📂 Project Structure
Alzheimer-CNN-Project
│
├── dataset/
│   ├── MildDemented
│   ├── ModerateDemented
│   ├── NonDemented
│   └── VeryMildDemented
│
├── notebooks/
│   └── ALZHEIMERS_PROJECT.ipynb
│
├── models/
│   └── cnn_model.h5
│
├── results/
│   ├── accuracy_graph.png
│   └── predictions.png
│
├── app.py
│
└── README.md
📊 Dataset

The dataset contains MRI brain images categorized into four classes.

Class	Description
NonDemented	Healthy brain
VeryMildDemented	Early stage
MildDemented	Moderate stage
ModerateDemented	Advanced stage

📥 Dataset Download

👉 Add your dataset link here:

https://www.kaggle.com/datasets/your-dataset-link
⚙️ Model Architecture

The CNN model includes:

Convolution Layers

Batch Normalization

MaxPooling Layers

Dropout Layers

Dense Layers

Softmax Output Layer

These layers help the model extract meaningful features from MRI images.

📈 Model Training
Parameter	Value
Image Size	128 × 128
Epochs	20
Optimizer	Adam
Loss Function	Categorical Crossentropy

The model learns patterns from MRI scans corresponding to Alzheimer stages.

📊 Model Results

Example performance:

Metric	Value
Training Accuracy	95%
Validation Accuracy	92%
Loss	0.21

(Replace with your actual results)

🖼️ Prediction Examples
MRI Prediction

Add screenshots here after running your model.

results/predictions.png

Example images:

MRI scan input

Model predicted stage

Accuracy score

📉 Training Accuracy Graph

Add the training graph screenshot:

results/accuracy_graph.png

This shows:

Training accuracy

Validation accuracy

Loss reduction

🖥️ How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/yourusername/alzheimer-cnn-project.git
cd alzheimer-cnn-project
2️⃣ Install Dependencies
pip install tensorflow numpy pandas matplotlib scikit-learn pillow streamlit
3️⃣ Run the Notebook
jupyter notebook

Open:

ALZHEIMERS_PROJECT.ipynb
🌐 Run Web App (Optional)

To test predictions using a simple web interface:

streamlit run app.py

Open in browser:

http://localhost:8501

Upload an MRI image and the model will predict the Alzheimer stage.

💡 Future Improvements

Possible improvements:

Transfer Learning using ResNet / VGG16

Explainable AI using Grad-CAM

Larger medical datasets

Cloud deployment

Integration with healthcare systems

🧑‍💻 Author

George Edayadil

AI / Machine Learning Enthusiast
Interested in:

Medical AI

Computer Vision

Deep Learning
