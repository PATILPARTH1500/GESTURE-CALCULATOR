<h1 align="center">🖐️🧠 Gesture Calculator</h1>
<p align="center">
  A Real-Time, Hands-Only Math Solver Using <strong>OpenCV</strong> and <strong>MediaPipe</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7--3.10-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-RealTime-green?logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Mediapipe-HandTracking-orange?logo=google&logoColor=white" />
</p>

---

## 📸 Demo

> 🎥 Add your demo GIF or YouTube link here  
> _“Watch how you can solve math using only your hands!”_

---

## 🚀 Features

- 🧠 Real-time hand gesture recognition
- 🔢 Supports full number entry (multi-digit input)
- ➕ Perform math operations: `+`, `-`, `*`, `/`
- ✅ Evaluate expression with gesture-based `=`
- 🔄 Clear or delete inputs using specific hand signs
- 🖥️ Works with any standard webcam
- 🖐️ Hands-only — no keyboard, no mouse

---

## 🛠️ Tech Stack

| Tool        | Role                                |
|-------------|--------------------------------------|
| Python      | Core programming language            |
| OpenCV      | Video capture & frame rendering      |
| MediaPipe   | Hand landmark detection (21 points)  |
| NumPy       | Math calculations & gesture logic    |

---

## ✋ Gesture Controls

| 🤚 Gesture                              | 🧮 Action            |
|----------------------------------------|----------------------|
| 1–5 fingers (one hand)                 | Digits 1–5           |
| 5 fingers (one) + 1–4 (other hand)     | Digits 6–9           |
| One closed hand (fist)                | Digit 0              |
| 1 finger on both hands                 | `+` (Addition)       |
| 1 + 2 fingers                          | `-` (Subtraction)    |
| 1 + 3 fingers                          | `*` (Multiplication) |
| 1 + 4 fingers                          | `/` (Division)       |
| Both hands closed                      | `=` (Evaluate)       |
| Both hands open (all 10 fingers)       | Clear input          |
| 2 fingers on each hand                 | Delete last input    |
| Right index to left of left index      | Exit program         |

---


## 📦 Installation

Make sure you're using **Python 3.7–3.10**. MediaPipe doesn't support newer versions like 3.11 or 3.12.

```bash
# Create virtual env (optional but recommended)
python -m venv venv
venv\Scripts\activate  # On Windows

# Install dependencies
pip install opencv-python mediapipe numpy

