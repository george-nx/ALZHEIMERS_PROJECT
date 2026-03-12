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

Alzheimer’s disease is a progressive brain disorder that slowly destroys memory and thinking skills. Diagnosing it early is critical for treatment and patient care.

Manual analysis of MRI scans is time-consuming and depends heavily on expert radiologists.

This project uses AI-based image classification to automatically identify Alzheimer stages from MRI scans.

🧠 Deep Learning Approach

The model uses Convolutional Neural Networks (CNN) built with:

TensorFlow

Keras

CNNs are well suited for image recognition tasks because they automatically learn spatial features such as patterns, shapes, and textures from images.

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

📊 Dataset

The dataset contains MRI brain images categorized into four classes:

Class	Description
NonDemented	Healthy brain
VeryMildDemented	Early stage
MildDemented	Moderate stage
ModerateDemented	Advanced stage

Images are resized and normalized before training the CNN model.

⚙️ Model Architecture

The CNN model includes:

Convolution Layers for feature extraction

Batch Normalization for training stability

MaxPooling Layers for dimensionality reduction

Dropout Layers to prevent overfitting

Dense Layers for classification

Softmax output layer for multi-class prediction

📈 Model Training

Training parameters:

Parameter	Value
Image Size	128 × 128
Epochs	20
Optimizer	Adam
Loss Function	Categorical Crossentropy

The model learns patterns in MRI scans that correspond to different Alzheimer stages.

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

To test predictions using a simple interface:

streamlit run app.py

Then open in browser:

http://localhost:8501

Upload an MRI image to see the predicted Alzheimer stage.

📊 Results

The model produces:

Training Accuracy & Validation Accuracy

Loss curves

MRI image predictions

Confusion matrix evaluation

These results demonstrate the ability of CNN models to detect patterns in medical images.

💡 Future Improvements

Possible enhancements:

Transfer Learning using **ResNet or **VGG16

Grad-CAM visualization for explainable AI

Larger MRI datasets

Model deployment on cloud

Integration with hospital systems

🧑‍💻 Author

George Edayadil

AI / Machine Learning Enthusiast
Interested in Medical AI, Computer Vision, and Deep Learning
