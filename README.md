# 🎯 Moving Object Detection using OpenCV

This project is a simple real-time **moving object detection system** built with Python and OpenCV. It uses a webcam to detect motion by comparing the current video frame to an initial reference frame.

---

## 📷 Features

- Real-time webcam feed
- Motion detection using frame differencing
- Highlights moving objects with bounding boxes
- Displays detection status (`Normal` / `Moving Object detected`)

---

## 🚀 Getting Started

### 📦 Requirements

- Python 3.x
- OpenCV
- imutils

Install the required libraries:

```bash
pip install -r requirements.txt
```

## ▶️ Usage
Run the script:
```
python motion_detector.py
```

Press Q to quit the program at any time.


## 🧠 How It Works
- Captures frames from your webcam
- Converts them to grayscale and applies Gaussian blur
- Compares the current frame with the first frame (reference)
- Detects significant differences (i.e., motion)
- Draws rectangles around moving objects

---
## 📁 Project Structure
```
Moving-Object-Detection/
│
├── motion_detector.py       # Main Python script
├── requirements.txt         # Python dependencies
├── .gitignore               # Git exclusions
└── README.md                # This file

```


## 🛠 Built With

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [imutils](https://github.com/jrosebr1/imutils)

## 🙋‍♂️ Author

**Thanusan S**  
GitHub: [@ThanusanS](https://github.com/ThanusanS)


