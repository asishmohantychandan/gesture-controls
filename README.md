# Gesture Control 🎮🖐️

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange)
![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-Automation-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

### Control Google Slides Presentations Using Hand Gestures

Real-time gesture recognition powered by Computer Vision and AI using OpenCV, MediaPipe, and PyAutoGUI.

</div>

---

## 📌 Overview

Gesture Control is an AI-powered Computer Vision application that enables users to control Google Slides presentations using hand gestures through a laptop webcam.

The system detects hand landmarks in real time and maps specific gestures to presentation commands, creating a hands-free presentation experience without requiring additional hardware.

This project demonstrates practical applications of:

* Computer Vision
* Human-Computer Interaction (HCI)
* Real-Time Gesture Recognition
* AI-Based Hand Tracking
* Desktop Automation

---

## 🚀 Features

✅ Real-time hand tracking using AI

✅ Control Google Slides without touching the keyboard

✅ Webcam-based interaction

✅ Lightweight and easy to use

✅ Beginner-friendly Computer Vision project

✅ No additional hardware required

✅ Cross-platform Python implementation

---

## 🧠 Gesture Controls

| Gesture          | Action          |
| ---------------- | --------------- |
| ✋ Open Palm      | Next Slide      |
| 🤟 Three Fingers | Previous Slide  |
| ✌️ Two Fingers   | Start Slideshow |
| ✊ Fist           | Exit Slideshow  |

---

## 🏗️ System Workflow

```text
Webcam Feed
      │
      ▼
OpenCV Video Capture
      │
      ▼
MediaPipe Hand Detection
      │
      ▼
Hand Landmark Extraction
      │
      ▼
Gesture Recognition Logic
      │
      ▼
PyAutoGUI Keyboard Commands
      │
      ▼
Google Slides Control
```

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* OpenCV
* MediaPipe
* PyAutoGUI

### Concepts

* Computer Vision
* Hand Landmark Detection
* Gesture Recognition
* Real-Time Video Processing
* Automation

---

## 📂 Project Structure

```text
gesture-controls/
│
├── .gitignore
├── README.md
├── requirements.txt
├── setup_models.py
├── main.py
│
└── models/
    └── hand_landmarker.task
```

---

## 📦 Installation

### Step 1 — Clone the Repository

```bash
git clone https://github.com/asishmohantychandan/gesture-controls.git
```

### Step 2 — Navigate to Project Directory

```bash
cd gesture-controls
```

### Step 3 — Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 4 — Download MediaPipe Model

```bash
python setup_models.py
```

---

## ▶️ Run the Application

```bash
python main.py
```

---

## 🎯 How to Use

1. Open Google Slides in Chrome.
2. Launch presentation mode.
3. Run the application.
4. Allow webcam access if prompted.
5. Show supported gestures in front of the camera.
6. Control slides hands-free.

---

## 📜 Requirements

### Python Version

```text
Python 3.10+
```

### requirements.txt

```txt
mediapipe==0.10.35
opencv-python>=4.8.0
pyautogui>=0.9.54
```

---

## 💻 macOS Permissions

For keyboard automation to work correctly:

Navigate to:

```text
System Settings
    → Privacy & Security
        → Accessibility
        → Input Monitoring
```

Grant access to:

* Terminal
* VS Code
* PyCharm

Without these permissions, slide control may not function.

---

## 🧩 How It Works

The application follows five major steps:

### 1. Webcam Capture

OpenCV continuously captures frames from the webcam.

### 2. Hand Detection

MediaPipe detects and tracks hand landmarks.

### 3. Landmark Analysis

Finger positions are analyzed to determine which gesture is being shown.

### 4. Gesture Mapping

Recognized gestures are mapped to predefined presentation commands.

### 5. Presentation Automation

PyAutoGUI simulates keyboard shortcuts to control Google Slides.

---

## 🔮 Future Improvements

* Swipe-based navigation
* Gesture-controlled laser pointer
* Volume control gestures
* Zoom in/out gestures
* Multi-hand support
* Custom gesture training
* Presentation annotation tools
* AI-powered gesture customization

---

## 🎓 Learning Outcomes

This project provides practical experience with:

* Computer Vision
* MediaPipe Framework
* Real-Time AI Systems
* Human-Computer Interaction
* Python Automation
* Webcam Processing
* Gesture Recognition Systems

---

## 💡 Use Cases

* Technical Presentations
* AI Workshops
* College Projects
* Hackathons
* Smart Classrooms
* Research Demonstrations
* Computer Vision Learning

---

## ⚠️ Best Practices

For optimal performance:

* Ensure adequate lighting.
* Keep your hand fully visible.
* Avoid cluttered backgrounds.
* Maintain a moderate distance from the camera.
* Use a stable webcam position.

---

## 🌐 Useful Resources

### MediaPipe Hand Tracking

https://google-ai-edge.github.io/mediapipe-samples-web/#/vision/hand_landmarker

### Google AI MediaPipe Documentation

https://ai.google.dev/edge/mediapipe/solutions/guide

---

## 🤝 Contributing

Contributions are welcome.

If you would like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Developer

**Asish Mohanty**

GitHub:
https://github.com/asishmohantychandan

Repository:
https://github.com/asishmohantychandan/gesture-controls

---

## ⭐ Support

If you found this project useful, consider giving the repository a star.

It helps support future AI and Computer Vision projects.
