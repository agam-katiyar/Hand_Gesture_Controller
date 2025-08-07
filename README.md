# 🤟 Hand Gesture Control System (Windows)

This project uses your **webcam** and **MediaPipe** to detect hand gestures and control system functions on **Windows**, including volume control, media playback, screenshots, locking the screen, opening File Explorer, and more.

---

## ✨ Features

- ✊ **Mute & Unmute** with Fist
- 🔊 **Volume Control** with Middle Finger or Thumb Down
- ⏯ **Play/Pause** (Media Keys / Spotify) using Peace Sign
- ⏭ / ⏮ **Swipe Right/Left** to go to Next/Previous Track
- 📂 **Open File Explorer** with “Call Me” Gesture
- 🖼️ **Take Screenshot** using Thumb + Index Gesture
- 🔒 **Lock Screen** with 4 Fingers Up, Thumb Down

---

## 🧠 How It Works

- Uses **MediaPipe** for real-time hand tracking and gesture recognition.
- Detected gestures are mapped to Windows system actions using:
  - `pycaw` for audio control
  - `pyautogui` for media key simulation and screenshots
  - `ctypes` for locking the screen
  - `subprocess` to launch apps like File Explorer

---

## 🛠️ Requirements

- Windows 10 or 11
- Python 3.7+
- pip (Python package manager)

---

## 🔧 Installation

Clone the repository and install required dependencies:

```bash
git clone https://github.com/agam-katiyar/Hand_Gesture_Controller/blob/main/handGestureController.py
cd hand-gesture-windows-control

pip install opencv-python mediapipe pycaw pyautogui comtypes numpy
