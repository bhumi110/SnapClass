# SnapClass | AI-Powered Smart Attendance System

<div align="center">

### 📸 Face Recognition • 🎤 Voice Authentication • ☁️ Cloud Database • ⚡ Streamlit

An intelligent attendance management system that automates classroom attendance using AI-powered face recognition with optional voice verification.

</div>

---

## 📖 Overview

SnapClass is a smart attendance platform designed to eliminate manual attendance processes by leveraging Artificial Intelligence and biometric authentication.

Students can securely register using their facial features (and optionally their voice), while teachers can create subjects, enroll students, and generate attendance records automatically.

The system combines modern computer vision, machine learning, and cloud databases to provide a seamless classroom experience.

---

## ✨ Features

### 👨‍🏫 Teacher Portal

- Secure teacher authentication
- Create and manage subjects
- Share subject enrollment codes
- View enrolled students
- Monitor attendance statistics
- Export attendance reports
- Dashboard with attendance analytics

---

### 👨‍🎓 Student Portal

- Face-based login
- AI-powered student registration
- Optional voice enrollment
- Subject enrollment using subject code
- View enrolled subjects
- Track attendance history
- One-click subject unenrollment

---

### 🤖 AI Features

- Face Detection
- Face Embedding Extraction
- Face Recognition
- Automatic Attendance Prediction
- Voice Embedding Generation
- Biometric Authentication
- Local AI Model Training
---
## Machine Learning Pipeline

### Face Recognition

- Capture Image
- Detect Face
- Generate Face Embeddings
- Train Classifier
- Predict Student Identity

### Voice Recognition

- Record Audio
- Generate Voice Embedding
- Store Embedding
- Verify Identity

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/snapclass.git

cd snapclass
```

### Create Virtual Environment

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv venv

source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```
---

## Configure Supabase

Create

```
.streamlit/secrets.toml
```

Add

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"

SUPABASE_KEY="YOUR_SUPABASE_API_KEY"
```

---

## Database

Execute the SQL schema inside your Supabase SQL Editor.

The project creates tables for

- Teachers
- Students
- Subjects
- Subject Enrollments
- Attendance Logs

---

## Running the Application

```bash
streamlit run app.py
```
