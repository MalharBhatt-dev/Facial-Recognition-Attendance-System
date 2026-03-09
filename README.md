# 📸 Facial Recognition Attendance System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv">
  <img src="https://img.shields.io/badge/InsightFace-Face%20Recognition-orange">
  <img src="https://img.shields.io/badge/ONNX-Runtime-yellow?logo=onnx">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
</p>

<p align="center">
  AI-powered attendance platform leveraging real-time facial recognition and deep learning inference.
</p>

---

# 🚀 Overview

The **Facial Recognition Attendance System** is a full-stack web application designed to automate attendance tracking using **computer vision and deep learning**.

The system integrates **InsightFace's Buffalo model** with **ONNX Runtime** to perform high-performance facial recognition inference. A **Flask-based backend** manages user enrollment, recognition workflows, and structured attendance logging.

This system provides a **contactless, secure, and scalable solution** for automating attendance management in educational institutions, organizations, and secure facilities.

---

# 🧠 Core Features

- 🎥 **Real-time facial detection** using webcam video streams  
- 🧠 **Deep learning-based face recognition** using InsightFace  
- ⚡ **High-performance inference** powered by ONNX Runtime  
- 👤 **Dynamic user enrollment system** for new users  
- 🕒 **Automated timestamped attendance logging**  
- 📊 **Structured attendance records for export and analysis**  
- 🔗 **ERP and backend system integration ready**

---

# 🛠 Technology Stack

| Layer | Technologies |
|------|-------------|
| **Backend** | Python, Flask |
| **Computer Vision** | OpenCV |
| **Face Recognition Model** | InsightFace (Buffalo Model) |
| **Inference Engine** | ONNX Runtime |
| **Frontend** | HTML, CSS, JavaScript |
| **Data Storage** | CSV / Structured Logs |

---

# ⚙️ System Architecture & Workflow

### 1️⃣ User Enrollment
Users register through the web interface where their facial images are captured and stored as embeddings.

### 2️⃣ Face Detection
OpenCV captures frames from the webcam and detects faces in real time.

### 3️⃣ Feature Extraction
The **InsightFace model** generates facial embeddings representing unique facial features.

### 4️⃣ Identity Matching
Generated embeddings are compared against stored embeddings to identify the user.

### 5️⃣ Attendance Logging
Recognized users are automatically logged with a **timestamped attendance entry**.

---

# 📂 Project Structure

```bash
Facial-Recognition-Attendance-System/
│
├── app.py                # Main Flask application
├── requirements.txt     # Project dependencies
│
├── static/              # CSS, JS, and frontend assets
├── templates/           # HTML templates
│
├── model/               # Face recognition models
├── utils/               # Helper functions and utilities
│
└── README.md
```

---

# ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MalharBhatt-dev/Facial-Recognition-Attendance-System
cd Facial-Recognition-Attendance-System
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
python app.py
```

---

### 5️⃣ Access the Application

Open your browser and visit:

```
http://localhost:5000
```

---

# 📌 Use Cases

- Educational institutions for automated attendance
- Corporate employee tracking systems
- Secure check-in and identity verification systems
- Smart campus or smart office solutions

---

# 🚧 Future Enhancements

- Role-based authentication system (Admin / User)
- Database integration (MySQL / PostgreSQL / MongoDB)
- Attendance analytics dashboard
- Cloud deployment support
- Face mask detection integration

---

# 📈 Potential Improvements

- Performance optimization for large user datasets
- Improved recognition accuracy in low-light environments
- Multi-camera support for larger deployment areas

---

# 📜 License

This project is **open-source** and distributed under the **MIT License**.
