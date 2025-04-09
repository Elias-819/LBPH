# 🧠 LBPH Face Recognition System with GUI (Tkinter + OpenCV)

## 🎯 Overview

This is a local face recognition system built using **Python**, **OpenCV**, and **Tkinter**. It supports:

- 📷 Real-time face detection via webcam  
- 🧠 Face data collection and automatic sample storage  
- 🏷️ Face model training using **LBPH** (Local Binary Patterns Histograms)  
- 👤 Identity recognition using a webcam  
- 🖥️ Simple and user-friendly GUI built with Tkinter  

---

## ⚙️ Requirements

- **Recommended Python version:** 3.6

### Install required packages:

pip install opencv-contrib-python==3.4.14.51
pip install numpy
pip install pillow

---

## 🧍‍♂️ Register a New Face
Click the "Register Face" button to:

- 📸 Capture 30 samples of a new user's face

- 🧠 Automatically train a new LBPH recognition model

- 📝 Save user information to the config.txt file
  
## 🕵️‍♂️ Face Recognition
Click the "Start Recognition" button to:

- 🔍 Detect a face in real-time via webcam

- 🧾 Match it against all trained face models

- 📌 Display the user's name and confidence score on screen

## ❌ Exit
- Click the "Exit" button to:

- 🛑 Close the application

- 🔓 Release the webcam and clean up resources
