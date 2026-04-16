# 🎨 Air Canvas – Gesture-Based Drawing System

## 📌 Overview

Air Canvas is a real-time computer vision application that allows users to draw in the air using hand gestures instead of a physical input device. The system uses hand tracking and gesture recognition to translate finger movements into drawing strokes on a virtual canvas.

---

## 🚀 Features

* Real-time hand tracking using MediaPipe
* Gesture-based drawing using index finger
* Multi-color drawing support (Blue, Green, Red, Yellow)
* Clear canvas functionality
* Smooth drawing using continuous point tracking

---

## 🧠 Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy

---

## ⚙️ How It Works

### 1. Hand Detection

* MediaPipe is used to detect hand landmarks (21 key points)
* Index finger tip is used for drawing

### 2. Gesture Recognition

* Distance between thumb and index finger is used to detect gestures
* Close fingers → stop drawing
* Finger in top region → UI interaction

### 3. Drawing Mechanism

* Finger positions are stored using deque
* Lines are drawn between consecutive points
* Separate arrays are maintained for each color

### 4. User Interface

* Buttons for color selection and clearing canvas
* Implemented using OpenCV rectangles and text

---

## 🧪 Key Concepts Used

* Real-time video processing
* Object tracking
* Gesture recognition
* Image preprocessing

---

## 📊 Challenges Faced

* Handling noise and unstable detection
* Lighting variations affecting tracking
* Ensuring smooth real-time performance

---

## 💡 Improvements

* Add more gesture controls (erase, shapes)
* Improve accuracy using deep learning models
* Add multi-hand support

---

## 🎯 Conclusion

This project demonstrates how computer vision can be used to build intuitive human-computer interaction systems using gestures, enabling touchless interaction.
