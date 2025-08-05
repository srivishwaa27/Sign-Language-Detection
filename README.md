🧠 Sign Language Detection using CNN (Indian Dataset)
📌 Project Overview
This project aims to develop a Sign Language Detection System using a Convolutional Neural Network (CNN) trained on an Indian Sign Language dataset consisting of A-Z alphabets and numbers 1-9. The system allows users to either upload an image or use real-time webcam detection, but only within a time-restricted window (6 PM to 10 PM).

Dataset: https://www.kaggle.com/datasets/prathumarikeri/indian-sign-language-isl
🎯 Features
Trained CNN model to recognize Indian sign language
Real-time video sign detection using webcam
Image upload-based detection
Time-based access control (operational only from 6 PM to 10 PM)
User-friendly GUI built with Tkinter

🗂️ Dataset Details
Indian Sign Language dataset
Contains folders for alphabets (A-Z) and numbers (1-9)
Each folder contains multiple images of hand gestures

⚙️ Model Architecture
CNN with 3 convolutional layers + max pooling
Fully connected dense layers with dropout
Output layer with softmax activation
Trained with categorical_crossentropy loss and Adam optimizer

🧪 Model Performance
Training Accuracy: >99%
Validation Accuracy: 100%
Loss: Very low (val_loss ≈ 0.0002)

🖥️ GUI Features
Upload Image: Allows image-based gesture recognition
Start Video: Enables webcam-based real-time detection
Stop Video: Stops webcam capture
Prediction Output: Displays the recognized sign
Time Restriction: Ensures usage is allowed only from 6 PM to 10 PM

🧰 Tech Stack
Python
TensorFlow / Keras
OpenCV
Tkinter (for GUI)
PIL (for image display in GUI)
Scikit-learn (Label encoding)

🏁 How to Run
Clone the repo and place the dataset in the specified structure.
Run the training script to train and save the model.
Launch the GUI application to interact with the system.
