# 📸 Facial Recognition Attendance System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask" />
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv" />
  <img src="https://img.shields.io/badge/ONNX-Runtime-orange?logo=onnx" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

<p align="center">
  AI-powered attendance system using real-time facial recognition and deep learning inference.
</p>

---

## 🚀 Overview

The **Facial Recognition Attendance System** is a full-stack web-based application designed to automate attendance tracking using computer vision and deep learning technologies.

The system leverages **InsightFace (Buffalo model)** with **ONNX Runtime** for high-accuracy facial recognition and integrates with a Flask backend to log structured attendance records in real time.

It provides a secure, contactless, and scalable alternative to traditional attendance systems.

---

## 🧠 Key Features

- 🎥 Real-time face detection via webcam  
- 🧠 Deep learning-based facial recognition  
- ⚡ Optimized inference using ONNX Runtime  
- 👤 Dynamic user enrollment system  
- 🕒 Automated timestamped attendance logging  
- 📊 Structured and exportable attendance records  
- 🔗 ERP/backend integration ready  

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | Python, Flask |
| **Computer Vision** | OpenCV |
| **Face Recognition Model** | InsightFace (Buffalo Model) |
| **Inference Engine** | ONNX Runtime |
| **Frontend** | HTML, CSS, JavaScript |
| **Storage** | CSV / Structured Logs |

---

## 🧩 System Workflow

### 1️⃣ User Enrollment  
>Users register their facial data via the web interface.

### 2️⃣ Face Detection & Embedding Extraction  
>OpenCV captures video frames and detects faces in real time.

### 3️⃣ Model Inference  
>InsightFace generates face embeddings using ONNX Runtime for optimized performance.

### 4️⃣ Face Matching  
>Extracted embeddings are compared with stored embeddings to identify individuals.

### 5️⃣ Attendance Logging  
>Recognized users are automatically logged with timestamped attendance records.

---

## 📂 Project Structure

```bash
Facial-Recognition-Attendance-System/
│
├── app.py
├── requirements.txt
├── static/
├── templates/
├── model/
├── utils/
└── README.md
```
---

## ⚙️ Installation & Setup
###       1️⃣ Clone the Repository
```bash
git clone https://github.com/MalharBhatt-dev/Facial-Recognition-Attendance-System
cd Facial-Recognition-Attendance-System
```
### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
```
#### Activate it:
>Windows
```bash
venv\Scripts\activate
```
>Mac/Linux
```bash
source venv/bin/activate
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Application
```bash
python app.py
```
### 5️⃣ Access the Web App
>Open your browser and navigate to:
```bash
http://localhost:5000
```
---
## 📌 Use Cases

- Educational institutions
- Corporate workforce tracking
- Secure check-in systems
- Smart campus solutions

---
## 🚧 Future Enhancements

- Role-based authentication (Admin / User)
- Database integration (MySQL / MongoDB)
- Attendance analytics dashboard
- Cloud deployment support
- Face mask detection support

---
## 📈 Potential Improvements

- Performance optimization for large datasets
- Improved recognition under low-light conditions
- Multi-camera support

---
## 📜 License

*This project is open-source and available under the MIT License.*
