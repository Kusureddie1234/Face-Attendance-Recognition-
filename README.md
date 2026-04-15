# 🎯 Face Attendance System

A Face Recognition-based Attendance System built using Python and Machine Learning to automate attendance marking using real-time face detection.

---

## 📌 Overview
This project uses computer vision techniques to detect and recognize faces through a webcam. It automatically marks attendance by comparing facial embeddings with stored data.

---

## 🚀 Features
- ✅ Real-time face detection
- ✅ Face recognition using embeddings
- ✅ Automatic attendance marking with date & time
- ✅ Duplicate attendance prevention
- ✅ Attendance stored in CSV file

---

## 🛠️ Technologies Used
- Python
- OpenCV
- MediaPipe
- DeepFace
- NumPy
- Pandas

---

## 🧠 How It Works
1. Face images are captured and stored
2. The system converts faces into embeddings (numerical vectors)
3. During attendance:
   - Live face is detected
   - Compared with stored embeddings
   - If matched → attendance is marked
4. Attendance is saved with date and time in a CSV file

---

## 📂 Project Structure
