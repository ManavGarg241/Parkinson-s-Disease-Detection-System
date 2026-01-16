# 🧠 Parkinson’s Disease Detection System

A full-stack deep learning application that detects Parkinson’s Disease from hand-drawn spiral and wave images using a Convolutional Neural Network (CNN). The system provides a web interface, secure authentication, and persistent storage for predictions.

---

## 📌 Overview

Parkinson’s Disease affects motor control, which is often reflected in hand-drawn patterns such as spirals and waves. This project uses deep learning and image processing techniques to classify these drawings as either Healthy or Parkinson’s Affected, offering an end-to-end deployable solution.

---

## 🚀 Features

- CNN-based image classification using TensorFlow and Keras
- FastAPI backend for serving ML predictions
- JWT-based user authentication (Login / Signup)
- Image preprocessing using OpenCV
- SQLite database with SQLAlchemy ORM
- Prediction history and admin statistics
- Web-based frontend for image upload and result display

---

## 🏗️ Project Structure

Parkinson-s-Disease-Classifier/
│
├── backend/
│   ├── main.py          # FastAPI application and ML inference
│   ├── models.py        # Database models
│   ├── database.py      # Database configuration
│   └── requirements.txt
│
├── frontend/
│   ├── HTML, CSS, JavaScript files
│
├── dataset/
│   ├── healthy/
│   └── parkinson/
│
├── create_admin.py      # Admin creation script
├── parkinsons.db        # SQLite database
└── README.md

---

## 🧪 How It Works

1. User uploads a hand-drawn spiral or wave image
2. Image is preprocessed using OpenCV
3. Processed image is passed to a trained CNN model
4. Model predicts:
   - Healthy
   - Parkinson’s Detected
5. Result is stored in the database and returned via API

---

## 🛠️ Tech Stack

- Python
- TensorFlow, Keras
- FastAPI
- OpenCV, NumPy
- SQLAlchemy, SQLite
- JWT Authentication
- HTML, CSS, JavaScript

---

## ⚙️ Installation & Setup

### Clone the repository
git clone https://github.com/your-username/Parkinson-s-Disease-Classifier.git
cd Parkinson-s-Disease-Classifier

### Install dependencies
pip install -r backend/requirements.txt

### Run the backend server
uvicorn backend.main:app --reload

### Access the application
- API Documentation: http://127.0.0.1:8000/docs
- Frontend: Open frontend/index.html in browser

---

## 🔐 Authentication

- OAuth2 with JWT tokens
- Secure password hashing
- Role-based access (User / Admin)

---

## 📊 Dataset

- Hand-drawn spiral and wave images
- Two classes:
  - Healthy
  - Parkinson
- Images are resized and normalized before inference

---

## 📈 Future Enhancements

- Add model evaluation metrics (Accuracy, Precision, Recall)
- Deploy on cloud platforms
- Improve frontend using modern frameworks
- Add analytics dashboard

---

## 👨‍🎓 Academic Use

This project was developed as a major academic project for Computer Science Engineering, demonstrating applied skills in Artificial Intelligence, backend development, and system integration.

---
