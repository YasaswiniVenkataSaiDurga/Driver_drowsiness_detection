#🚗 Driver_drowsiness_detection 💤

This project uses *computer vision and machine learning* to detect driver drowsiness in real-time. It monitors eye movements using facial landmarks and alerts the driver if drowsiness is detected — potentially preventing accidents caused by fatigue.

## 🔍 Problem Statement
Drowsiness during driving leads to severe road accidents worldwide. Detecting and preventing such drowsiness is crucial to saving lives. This system aims to provide a *real-time alert mechanism* when the driver becomes drowsy.

## 🎯 Features
- Real-time video processing with webcam.
- Facial and eye landmark detection using *Dlib*.
- Calculates *Eye Aspect Ratio (EAR)* to detect eye closure.
- Displays *visual alerts* and plays *sound beeps* on drowsiness detection.
- Works offline — no internet required.

## ⚙️ Technologies Used
- Python
- OpenCV
- Dlib (with shape predictor)
- SciPy, NumPy
- Winsound (for alert)

## 🖥️ Installation

### 🔗 Pre-requisites
- Python 3.7+
- Webcam
- shape_predictor_68_face_landmarks.dat file (Download from [dlib model page](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)
