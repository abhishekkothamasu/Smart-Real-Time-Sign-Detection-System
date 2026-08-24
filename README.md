# Smart Real-Time Sign Detection System

## 📌 Project Overview

The **Smart Real-Time Sign Detection System** is a web-based application designed to recognize hand gestures in real time and convert them into meaningful text and speech. The system uses a webcam to capture hand gestures, processes them using computer vision techniques, and applies machine learning models for gesture and alphabet recognition.

The project is designed to improve communication for speech-impaired individuals by providing a simple interface where recognized gestures can be converted into text and audible speech.

## 🎯 Key Features

* Real-time hand gesture recognition using a webcam
* Hand landmark detection using **MediaPipe**
* Image and gesture processing using **OpenCV**
* Machine learning-based gesture and alphabet recognition
* Conversion of recognized gestures into text
* Text-to-speech functionality using **pyttsx3**
* Sentence formation using **NLTK**
* Predefined emergency gestures for hospital environments
* Automatic SMS alerts using the **Twilio API**
* Real-time emergency notifications on an admin dashboard
* Secure user authentication
* User data management and database integration

## 🛠️ Technologies Used

### Programming Language

* Python

### Web Technologies

* Flask
* HTML
* CSS
* JavaScript

### Machine Learning & Computer Vision

* TensorFlow
* Scikit-learn
* OpenCV
* MediaPipe
* NLTK

### Database & Authentication

* Flask-SQLAlchemy
* Flask-Login
* Flask-Bcrypt
* SQL / MySQL / MS SQL Server

### APIs & Tools

* Twilio API
* Jupyter Notebook
* GitHub

## ⚙️ System Workflow

1. The user accesses the web application.
2. The webcam captures the user's hand gestures.
3. OpenCV processes the camera input.
4. MediaPipe detects and extracts hand landmarks.
5. The extracted features are passed to machine learning models.
6. The system identifies the corresponding gesture or alphabet.
7. The recognized gesture is converted into text.
8. NLTK assists with sentence formation.
9. The generated text can be converted into speech.
10. If an emergency gesture is detected, the system sends an SMS through Twilio.
11. The emergency notification is displayed on the admin dashboard.

## 🚨 Emergency Gesture Detection

A special feature of this project is the **emergency gesture detection system** designed for hospital environments.

Predefined gestures can be recognized and used to trigger automated alerts. When an emergency gesture is detected, the application can send an SMS notification through the **Twilio API** and display a real-time notification on the administrator's dashboard.

## 🔐 Authentication & Security

The application includes secure user authentication and data management using:

* **Flask-Login** for user session management
* **Flask-Bcrypt** for password security
* **Flask-SQLAlchemy** for database operations

These components help provide secure access to the application and manage user-related information.

## 📂 Project Structure

```text
Smart-Real-Time-Sign-Detection/
│
├── app.py
├── models/
├── templates/
├── static/
├── dataset/
├── models/
├── utils/
├── requirements.txt
└── README.md
```

> The exact folder structure may vary depending on your implementation.

## 🚀 Future Enhancements

* Improve recognition accuracy for complex gestures
* Add support for more sign language gestures
* Expand emergency gesture categories
* Improve real-time processing performance
* Add multilingual text-to-speech support
* Deploy the application to a cloud platform
* Develop a mobile application version

## 👨‍💻 Project Purpose

The main objective of this project is to develop an accessible communication system that bridges the communication gap between speech-impaired individuals and others by combining **web development, computer vision, machine learning, natural language processing, and real-time communication APIs**.

## 📜 Conclusion

The Smart Real-Time Sign Detection System demonstrates the practical application of Python, Flask, computer vision, machine learning, and API integration to build an end-to-end real-time communication solution. The project combines gesture recognition, text-to-speech conversion, authentication, database management, and emergency alert functionality in a single web application. 
