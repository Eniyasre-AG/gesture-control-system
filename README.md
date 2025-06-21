# Gesture Control System 💻✋

A Python-based gesture recognition system using **MediaPipe**, **OpenCV**, and **PyAutoGUI** to control mouse, scroll, brightness, and volume with hand gestures. This project enables contactless interaction with your computer using real-time webcam input.

---

## ✨ Features

- 🖱️ **Mouse Control** via hand movement
- 👊 **Click and Drag** using Fist gesture
- ✌️ **V Gesture** for enabling precise pointer tracking
- 🖐️ **Gesture-based Clicks**
  - Mid finger for **left click**
  - Index finger for **right click**
  - Two fingers closed for **double click**
- 📉 **Scroll** horizontally and vertically using **Pinch with Left Hand**
- 💡 **Adjust System Brightness** using **Pinch with Right Hand (X-axis)**
- 🔊 **Adjust Volume** using **Pinch with Right Hand (Y-axis)**

---

## 🛠️ Technologies Used

- [Python](https://www.python.org/)
- [MediaPipe](https://google.github.io/mediapipe/)
- [OpenCV](https://opencv.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)
- [pycaw](https://github.com/AndreMiras/pycaw) (for volume control)
- [screen-brightness-control](https://github.com/Crozzers/screen_brightness_control)

---

## 📷 Gesture Guide

| Gesture | Action |
|--------|--------|
| ✌️ V Gesture | Enable tracking |
| 👊 Fist | Left click + drag |
| ☝️ Index | Right click |
| 🖖 Mid Finger | Left click |
| 🤏 Pinch (Left Hand) | Scroll |
| 🤏 Pinch (Right Hand) | Adjust Brightness / Volume |

---

## 🚀 How to Run

### 🔧 Requirements

Install dependencies:

```bash
pip install opencv-python mediapipe pyautogui pycaw screen-brightness-control protobuf comtypes
---

###▶️ Run the project
python main.py


