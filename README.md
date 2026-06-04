# 🎓 SnapClass AI Attendance System

<div align="center">

### 🚀 AI-Powered Smart Classroom Attendance Platform

Take attendance in seconds using **Face Recognition** and **Voice Verification**.

🌐 **Live Demo:** https://snap-class-attendance-using-ai.streamlit.app

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-red?style=for-the-badge\&logo=streamlit)
![Supabase](https://img.shields.io/badge/Supabase-Database-green?style=for-the-badge\&logo=supabase)
![AI](https://img.shields.io/badge/AI-Face%20%26%20Voice-purple?style=for-the-badge)

</div>

---

## 📖 Overview

**SnapClass** is an intelligent classroom attendance system that automates attendance management using advanced Artificial Intelligence.

Instead of manually calling names, teachers can simply:

📸 Capture a classroom image for Face Recognition

🎙️ Record classroom audio for Voice Verification

⚡ Generate attendance instantly

The platform is designed for educational institutions seeking a faster, smarter, and more secure attendance process.

---

## 🌟 Key Features

### 👨‍🏫 Teacher Portal

#### 🔐 Secure Authentication

* Teacher registration & login
* Password hashing using BCrypt
* Protected dashboard access

#### 📚 Subject Management

* Create unlimited subjects
* Unique enrollment codes
* Section-wise organization
* One-click sharing links

#### 📸 AI Face Attendance

* Upload classroom photos
* Detect multiple faces simultaneously
* Dlib face embeddings
* SVM-based student recognition

#### 🎤 AI Voice Attendance

* Record classroom audio
* Automatic speaker segmentation
* Voice identity verification
* Resemblyzer embedding matching

#### 📊 Attendance Analytics

* Historical attendance logs
* Session records
* Attendance statistics
* Presence reports

---

### 🎓 Student Portal

#### 😀 FaceID Login

* Camera-based authentication
* Password-free access
* Fast and secure login

#### 🎙️ Voice Enrollment

* Optional voice registration
* Enables voice attendance verification

#### 📚 Course Dashboard

* View enrolled subjects
* Attendance percentage tracking
* Quick course management

#### 🔗 Smart Enrollment

* Join subjects using enrollment codes
* Auto-enroll via shared links
* One-click registration

---

## 🧠 AI Architecture

### Face Recognition Pipeline

Student Face
↓
Dlib Face Detection
↓
128-D Face Embedding
↓
SVM Classification
↓
Student Identification

### Voice Recognition Pipeline

Audio Recording
↓
Audio Segmentation
↓
Resemblyzer Embeddings
↓
Similarity Matching
↓
Student Verification

---

## 🛠️ Tech Stack

| Category          | Technology      |
| ----------------- | --------------- |
| Frontend          | Streamlit       |
| Backend           | Python          |
| Database          | Supabase        |
| Face Recognition  | Dlib            |
| Machine Learning  | Scikit-Learn    |
| Voice Recognition | Resemblyzer     |
| Audio Processing  | Librosa         |
| Security          | BCrypt          |
| Deployment        | Streamlit Cloud |

---

## 📂 Project Structure

```text
snapclass_AI_atten/

├── .streamlit/
│   └── secrets.toml

├── src/
│
├── components/
│   ├── dialog_add_photo.py
│   ├── dialog_voice_attendance.py
│   ├── subject_card.py
│   └── ...
│
├── database/
│   ├── config.py
│   └── db.py
│
├── pipelines/
│   ├── face_pipeline.py
│   └── voice_pipeline.py
│
├── ui/
│   └── base_layout.py
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 🚀 Live Application

### 🌐 Try SnapClass Now

**Demo Link**

https://snap-class-attendance-using-ai.streamlit.app

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Om-patil-1091/snapclass_AI_Attendance.git

cd snapclass_AI_Attendance
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 🔑 Supabase Configuration

Create:

```text
.streamlit/secrets.toml
```

Add:

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"
SUPABASE_KEY="YOUR_SUPABASE_KEY"
```

---

## 🔒 Security

### Data Protection

✅ Face data stored as embeddings

✅ Voice data stored as embeddings

✅ No raw biometric data required

✅ BCrypt password hashing

✅ Secure authentication workflow

---

## 🎨 UI Highlights

* Modern Glassmorphism Design
* Dark & Light Theme Support
* Responsive Dashboard
* Interactive Cards
* Smooth User Experience
* Premium Typography

---
## 👨‍💻 Developer

### Om Patil

📧 Contact: Open an issue or connect through GitHub

GitHub Repository:

https://github.com/Om-patil-1091/snapclass_AI_Attendance

---

## ⭐ Support

If you like this project:

⭐ Star the repository

🍴 Fork the project

📝 Share feedback

🚀 Contribute improvements

---

<div align="center">

### Smart Attendance Powered by AI 🤖

Made with ❤️ using Streamlit, Supabase, Dlib and Resemblyzer

</div>
