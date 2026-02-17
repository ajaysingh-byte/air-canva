# air-canvas
# 🖐️ Air Canvas – Hand Gesture Drawing App

Air Canvas is a computer vision–based drawing application that allows users to draw in the air using hand gestures captured through a webcam. The project uses **MediaPipe Hands** for real-time hand tracking and **OpenCV** for video processing and drawing.

Users can select colors, draw, erase, and clear the canvas using simple finger gestures—no mouse or touch required.

---

## 🎯 Project Objective

The objective of this project is to demonstrate how **hand gesture recognition** and **computer vision** can be used to build interactive, touch-free applications using Python.

---

## ✨ Features

- Real-time hand tracking using webcam  
- Draw in the air using index finger  
- Color selection using index + middle finger  
- Built-in color palette (Purple, Blue, Green, Yellow)  
- Eraser functionality using gesture  
- Clear canvas using keyboard shortcut  
- Smooth drawing with dynamic stroke thickness  

---

## 🖐️ Hand Gesture Controls

| Gesture | Action |
|-------|--------|
| Index finger up | Draw |
| Index + Middle finger up | Select color |
| Select **Black** | Eraser |
| Press **C** | Clear canvas |
| Press **Q** | Quit application |

---

## 🧰 Technologies Used

- **Python 3**
- **OpenCV**
- **MediaPipe**
- **NumPy**
- **Webcam**

---

## 📂 Project Structure

```text
Air-Canvas/
│── air_canvas.py
│── README.md
│── requirements.txt
```
## ⚙️ Installation & Setup (Complete Steps)

Follow the steps below to set up and run the Air Canvas project on your system
### Step 1: Check Python Installation
```bash
python --version
```
### Step 2: Clone the Repository
```bash
git clone https://github.com/ajaysingh-byte/air-canva.git
cd air-canva
```
### Step 3: (Optional but Recommended) Create and Activate Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```
### Step 4: Install Dependencies from requirements.txt
```bash
pip install -r requirements.txt
```
### Step 6: Run the Application
```bash
python air_canvas.py
```
