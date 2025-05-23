# AI-based-proctored-exam-monitoring-system
# Face Recognition and Drowsiness Detection System with Exam Monitoring

A Python-based proctored exam monitoring system that ensures secure authentication, real-time candidate alertness tracking, and live exam supervision using face recognition, drowsiness detection, and activity monitoring.

## 📌 Project Description

This project addresses the challenges of online exam security by implementing:

- **Face Recognition Authentication**: Authenticate users using biometric facial recognition for secure exam access.
- **Drowsiness Detection**: Track candidate alertness in real-time through eye and head movement detection.
- **Exam Monitoring**: Continuously monitor and flag suspicious behavior to prevent cheating during online exams.

## 🎯 Problem Statement

- **Weak Authentication**: Traditional login systems are vulnerable to unauthorized access.
- **Cheating in Online Exams**: Studies indicate around 40% of students admit to dishonest behavior in online assessments.

## 🛠️ Technology Stack

- **Python**
- **OpenCV**
- **Deep Learning**
- **Haar Cascades**
- **Facial Landmark Detection (Dlib/MediaPipe)**

## 📊 System Features & Performance

- **98% Face Recognition Accuracy**
- **30% Reduction in False Positives**
- **Recognition Speed**: Under 0.5 seconds per frame
- **Drowsiness Detection via Eye Aspect Ratio (EAR)** and head position analysis
- **Alert Trigger**: Warning issued after 5 seconds of detected drowsiness

## 📖 Modules Overview

### 1️⃣ Face Recognition Module
- Uses Haar cascades for face detection
- Deep learning-based facial recognition for user authentication

### 2️⃣ Drowsiness Detection Module
- **Eye Aspect Ratio (EAR)** threshold set at 0.25 for monitoring
- Detects head orientation using 68 facial landmarks
- Issues alerts after 5 seconds of drowsiness detection

### 3️⃣ Exam Monitoring Module
- Live monitoring of candidate’s face, eye status, and head position
- Suspicious activities flagged in real time

## 📐 Architecture

- **Input**: Webcam video stream
- **Face Detection**: Haar cascade classifier
- **Face Recognition**: Deep learning model comparison
- **Drowsiness Monitoring**: EAR & head pose estimation
- **Proctor Alerts**: Real-time notifications on detected issues

## 📸 Demo

_Add screenshots or GIFs of your system in action here_

## 📌 Author

- **P. Yaswanth Kumar (22761A4244)**

## 📬 Contact

- 📧 yaswanthkumarp99@gmail.com

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).
