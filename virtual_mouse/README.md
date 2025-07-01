# 🖐️ Hand Gesture Mouse Controller

This project allows users to control mouse operations using hand gestures through a webcam. Built using **OpenCV**, **MediaPipe**, **PyAutoGUI**, and **NumPy**, it enables gesture-based control for:

- Moving the mouse
- Left click
- Right click
- Double click
- Taking a screenshot

---

## 🚀 Features

- ✅ Real-time hand tracking with **MediaPipe**
- ✅ Gesture recognition for common mouse actions
- ✅ Screenshot capture with a specific gesture
- ✅ Supports single-hand tracking
- ✅ Works on any screen resolution

---

## 🧠 How It Works

The application uses a webcam to detect your hand, tracks hand landmarks using MediaPipe, and calculates angles and distances between key finger joints to determine gestures.

| Gesture                           | Action            |
| --------------------------------- | ----------------- |
| Index finger forward              | Move mouse cursor |
| Index finger bent + thumb far     | Left click        |
| Middle finger bent + thumb far    | Right click       |
| Index + middle bent + thumb far   | Double click      |
| Index + middle bent + thumb close | Screenshot        |

---

## 🧰 Tech Stack

- **Python 3**
- [OpenCV](https://opencv.org/) – Computer vision
- [MediaPipe](https://mediapipe.dev/) – Hand tracking
- [PyAutoGUI](https://pyautogui.readthedocs.io/) – Mouse/screenshot control
- [NumPy](https://numpy.org/) – Math & geometry
- [Pynput](https://pynput.readthedocs.io/) – Mouse control backend

---

## 📦 Installation

````bash
# Clone the repository
git clone https://github.com/tiwariharsh007/GestureMouse.git
cd hand-gesture-mouse-controller

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

---

## ▶️ Usage

```bash
python main.py
````

Press **`q`** to quit the webcam window.

---

## 📁 File Structure

```text
hand-gesture-mouse-controller/
│
├── main.py         # Main script with OpenCV, MediaPipe, and gesture logic
├── util.py               # Utility functions for angle and distance calculations
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 🧑‍💻 Author

**Harsh Tiwari**

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).
