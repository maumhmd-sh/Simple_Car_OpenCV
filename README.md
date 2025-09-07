# 🚗 Simple_Car_OpenCV

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?style=flat-square&logo=opencv)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

---

## 📄 Project Description

**Simple_Car_OpenCV** is a beginner-friendly Python project that demonstrates vehicle detection in videos using OpenCV.  
It leverages a pre-trained Haar cascade classifier (`cars.xml`) to identify and highlight cars in the sample video (`mobil_1.mp4`).  
This project is perfect for learning the basics of computer vision and object detection.

---

## 📁 Repository Structure

Simple_Car_OpenCV/
├── Car_detection.py # Main detection script
├── cars.xml # Haar cascade classifier model for car detection
├── mobil_1.mp4 # Sample video for testing
└── README.md # Project documentation


---

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/maumhmd-sh/Simple_Car_OpenCV.git
cd Simple_Car_OpenCV
```
## 2. Install dependencies
```
pip install opencv-python
```

## 3. Run the detection script
```
python Car_detection.py
```

👉 The script will open the video file and display detected cars with bounding boxes.

---

## ✨ Features
- Detects cars in video using Haar cascade classifier.
- Real-time bounding box display for each vehicle.
- Lightweight and beginner-friendly codebase.
- Easy to extend for other object detection tasks.

## 🎬 Demo
Example: detected cars highlighted with bounding boxes.

## 📝 License
This project is licensed under the MIT License.

---

## ❤️ Support
If you find this project helpful for learning computer vision,
please give it a ⭐ on GitHub and share it with others!
