

# Doomscrolling Blocker 📱🚫

A Python app that uses your webcam to detect when you're looking down at your phone and roasts you back to work — with an automatic rickroll punishment 🎵

---

## 🚀 Features

* Real-time face tracking (OpenCV / dlib)
* Detects head tilt (looking down)
* Motivational roasting messages
* Auto rickroll video popup
* Video auto-closes when posture improves

---

## 📦 Installation

### Quick install

```bash
pip install -r requirements.txt
```

### Manual install

Basic:

```bash
pip install opencv-python numpy
```

Advanced (better accuracy):

```bash
pip install opencv-python numpy dlib
```

Download dlib face model (if using dlib):

```bash
wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
bunzip2 shape_predictor_68_face_landmarks.dat.bz2
```

---

## ⚙️ Setup

* Place `rickroll.mp4` in project folder
* Ensure default video player is installed
* Make sure webcam is connected

---

## ▶️ Run

```bash
python main.py
```

* Good posture → ✅ Green message
* Looking down → ❌ Roast + Rickroll
* Press `q` to quit

---

## 🛠 Requirements

* Python 3.13+
* Webcam
* OpenCV
* NumPy
* (Optional) dlib
* `rickroll.mp4`

---

## 🎯 Customization

Edit `main.py` to:

* Change roast messages
* Adjust detection sensitivity
* Modify roast timing
* Replace rickroll video

---

Stay productive 💪
