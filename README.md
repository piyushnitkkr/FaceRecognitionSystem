# Face Recognition Using OpenCV and KNN

A real-time face recognition system built with **OpenCV** and **K-Nearest Neighbors (KNN)**. This project captures faces from a webcam, stores them as NumPy arrays, and performs live face recognition by comparing them with saved data.

---

## 🔧 Features

- Face detection using Haar cascades
- Face data collection with webcam
- Save face data per person as `.npy` files
- Train a simple KNN classifier on the saved face data
- Real-time face recognition with webcam

---

## 📂 Folder Structure

project-root/
│
├── data/ # Folder where face .npy files are saved
│ └── person1.npy
│
├── haarcascade_frontalface_alt.xml # Haar cascade file for face detection
├── face_data_collection.py # Script to capture and save face data
├── face_recognition_knn.py # Script to run live recognition
├── README.md


---

## ▶️ How to Run

### 1. Install Requirements

```bash
pip install opencv-python numpy
