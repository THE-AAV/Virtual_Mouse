# 🖱️ Virtual Mouse

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)]()  
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)]()  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Control your computer mouse using **hand gestures** with Python!  
This project leverages **computer vision** and **MediaPipe** to detect and interpret hand movements, enabling pointer control, clicking, and dragging — all without a physical mouse.

---

## 📖 Overview
Virtual Mouse is an experimental project that demonstrates how computer vision can be applied to human-computer interaction.  
It uses a webcam to track your hand and translates gestures into mouse actions.

✨ **Key Features**
- Real-time hand gesture recognition  
- Control mouse pointer with finger movements  
- Click and drag functionality using gestures  
- Simple and easy-to-use interface  
- Built entirely in Python with OpenCV, MediaPipe, and PyAutoGUI  

---

## 📂 Project Structure
```
Virtual_Mouse/
├── Virtual_mouse.py   # Main script for gesture detection and mouse control
├── README.md          # Documentation
└── requirements.txt   # Dependencies
```

---

## ⚙️ Requirements
- Python 3.7 – 3.11 (recommended: 3.7.9)  
- Dependencies:
  - `mediapipe`
  - `opencv-python`
  - `pyautogui`

Install them with:
```bash
pip install mediapipe opencv-python pyautogui
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/THE-AAV/Virtual_Mouse.git
cd Virtual_Mouse
```

### 2. Run the project
```bash
python Virtual_mouse.py
```

---

## 🧪 How It Works
1. The webcam captures your hand movements.  
2. MediaPipe detects landmarks on your fingers.  
3. OpenCV processes the video feed.  
4. PyAutoGUI translates gestures into mouse actions.  

---

## 🔗 Example Gestures
- **Move pointer** → Move your index finger  
- **Click** → Pinch index finger and thumb together  
- **Drag** → Hold pinch and move  

---

## 📚 Learning Goals
This project helps you understand:
- Basics of computer vision with OpenCV  
- Gesture recognition using MediaPipe  
- Automating mouse actions with PyAutoGUI  
- Building intuitive human-computer interaction systems  

---

## 🤝 Contributing
Contributions are welcome!  
Fork the repo, submit issues, or open pull requests to add new gestures, improve accuracy, or enhance usability.

---

## 📜 License
This project is licensed under the MIT License.  
You are free to use, modify, and distribute it for educational and experimental purposes.

---
