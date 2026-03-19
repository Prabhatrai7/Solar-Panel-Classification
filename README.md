# 🌞 Solar Panel Condition Classification

A Deep Learning-based system to automatically classify solar panel conditions using image data. This project helps in identifying faults and environmental impacts affecting solar panel efficiency.

# 🚀 Problem Statement

Solar panels are exposed to real-world conditions that reduce their performance, such as dust, bird droppings, physical damage, electrical faults, and snow coverage.

Manual inspection of solar panels:

Is time-consuming

Requires human effort

Is not scalable for large solar farms

This project aims to automate the detection process using a multi-class image classification model.

#💡 Solution

Developed a Deep Learning model that classifies solar panel images into multiple categories, enabling faster and more efficient monitoring.

# 🧠 Classes

The model predicts the following 6 classes:

Bird-drop
Clean
Dusty
Electrical-damage
Physical-Damage
Snow-Covered

# ⚙️ Tech Stack

Python
TensorFlow / Keras
OpenCV
NumPy, Pandas
Matplotlib

# 📂 Project Structure
Solar-Panel-Classification/
│── dataset/
│   ├── Bird-drop/
│   ├── Clean/
│   ├── Dusty/
│   ├── Electrical-damage/
│   ├── Physical-Damage/
│   ├── Snow-Covered/
│
│── notebooks/
│── models/
│── src/
│── train.py
│── predict.py
│── requirements.txt
│── README.md

# 🔬 Model Details

Multi-class Image Classification
Built using CNN / Transfer Learning

Output Layer:
Dense(6, activation='softmax')

Loss Function:
categorical_crossentropy

# 🔄 Workflow

Data Preparation
Image Preprocessing & Augmentation
Model Training
Model Evaluation
Prediction

# 🚀 Getting Started

Clone Repository
git clone https://github.com/Prabhatrai7/Solar-Panel-Classification.git
cd Solar-Panel-Classification
Install Dependencies
pip install -r requirements.txt
Train Model
python train.py
Run Prediction
python predict.py

# 📊 Results

Successfully classifies solar panel conditions into 6 categories

Helps automate inspection and reduce manual effort

# 🔮 Future Enhancements

Improve accuracy using EfficientNet / ResNet

Deploy as a web application (Streamlit / Flask)

Integrate with real-time monitoring systems
