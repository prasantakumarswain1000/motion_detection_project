# 🎥 Motion Detection Using OpenCV

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/OpenCV-4.x-green?style=for-the-badge&logo=opencv">
  <img src="https://img.shields.io/badge/Computer%20Vision-Project-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

# 📌 Project Overview

The **Motion Detection Using OpenCV** project is a real-time computer vision application developed in **Python** using the **OpenCV** library. The system captures live video from a webcam, processes each frame, detects movement by comparing consecutive frames, and highlights moving objects with bounding rectangles.

This project demonstrates the fundamentals of computer vision, image processing, and real-time video analysis using OpenCV.

---

# 🚀 Features

- 🎥 Real-Time Motion Detection
- 📹 Live Webcam Video Capture
- 🖼️ Frame-by-Frame Video Processing
- 📦 Motion Highlighting with Bounding Boxes
- 🧹 Noise Reduction Using Morphological Operations
- ⚡ Fast and Lightweight
- 💻 Easy to Understand and Modify
- 🖥️ Cross-Platform Support

---

# 🛠️ Technologies Used

| Technology | Description |
|------------|-------------|
| Python | Programming Language |
| OpenCV | Computer Vision & Image Processing |
| NumPy | Numerical Operations |

---

# 📂 Project Structure

```
Motion-Detection/
│
├── motion_detection.py
├── README.md
├── requirements.txt
├── images/
│   ├── output1.png
│   ├── output2.png
│
└── assets/
```

---

# ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Motion-Detection.git
```

### Navigate to the Project

```bash
cd Motion-Detection
```

### Install Dependencies

```bash
pip install opencv-python numpy
```

Or install using:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

```bash
python motion_detection.py
```

After running the program:

- The webcam starts automatically.
- Motion is detected in real time.
- Moving objects are enclosed within a rectangle.
- Press **Q** to exit the application.

---

# 🔄 Workflow

```
Start Webcam
      │
      ▼
Capture Video Frames
      │
      ▼
Resize Frame (Optional)
      │
      ▼
Convert to Grayscale
      │
      ▼
Apply Gaussian Blur
      │
      ▼
Frame Difference
      │
      ▼
Thresholding
      │
      ▼
Morphological Operations
      │
      ▼
Find Contours
      │
      ▼
Draw Bounding Boxes
      │
      ▼
Display Live Motion Detection
```

---

# 🧠 OpenCV Concepts Used

- VideoCapture
- Frame Reading
- Grayscale Conversion
- Gaussian Blur
- Frame Differencing
- Binary Thresholding
- Image Dilation
- Image Erosion
- Morphological Opening
- Morphological Closing
- Contour Detection
- Bounding Rectangle
- Displaying Video Frames

---

# 📷 Expected Output

The application displays:

- 📹 Live Webcam Feed
- 🚶 Motion Detection in Real Time
- 🟥 Bounding Boxes Around Moving Objects

---

# 🎯 Applications

- 🏠 Home Security Systems
- 🎥 CCTV Surveillance
- 🏢 Office Monitoring
- 🚪 Intruder Detection
- 🚗 Parking Area Monitoring
- 🤖 Robotics
- 🏭 Industrial Automation
- 🌿 Wildlife Observation

---

# 📚 What I Learned

Through this project, I gained practical experience in:

- OpenCV Basics
- Real-Time Video Processing
- Image Processing Techniques
- Contour Detection
- Morphological Operations
- Motion Detection Algorithms
- Python Programming
- Computer Vision Fundamentals

---

# 🔮 Future Enhancements

- Face Detection
- Human Detection using YOLO
- Motion Recording
- Email Alert Notifications
- Cloud Storage Integration
- Multi-Camera Support
- Object Tracking
- AI-Based Motion Classification

---

# 📦 Requirements

```
Python 3.x
OpenCV
NumPy
```

Install dependencies:

```bash
pip install opencv-python numpy
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 👨‍💻 Developer

## **Prasanta Kumar Swain**

**Python Developer | OpenCV Enthusiast | Computer Vision Learner | MERN Stack Developer**

- 💻 Passionate about Python and Computer Vision
- 🚀 Building real-world AI and OpenCV projects
- 📚 Continuously learning new technologies

---

# ⭐ Show Your Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

---

# 📄 License

This project is licensed under the **MIT License**.

---

<p align="center">

## ❤️ Made with Python & OpenCV

### Developed by **Prasanta Kumar Swain**

🚀 Happy Coding!

</p>
