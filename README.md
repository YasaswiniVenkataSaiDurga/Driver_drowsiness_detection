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
- The shape_predictor_68_face_landmarks.dat file, required for this project, is too large to be hosted directly on GitHub. Please download it from the following link and place it in the data/ directory of this repository:

[Download shape_predictor_68_face_landmarks.dat (Google Drive)]([YOUR_DOWNLOAD_LINK_HERE](https://drive.google.com/drive/folders/1DcgB-4yZZ84vN2SKCTHCno_OCMA3EaQj?usp=drive_link))
