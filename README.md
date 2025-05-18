# Vehicle Speed Estimation using Perspective Transformation

🚗📷 A computer vision project to **track, count, and estimate vehicle speed** from surveillance footage using **perspective transformation (bird's eye view)**. Built with Python and OpenCV, this system allows users to define custom Regions of Interest (ROI) and converts pixel displacement into real-world speed estimation (km/h or m/s) using homography calibration.

## 🔍 Features
- Vehicle detection and tracking with centroid tracking
- ROI definition via manual point selection (mouse click)
- Perspective transformation (bird’s eye view) with homography
- Real-time speed estimation based on pixel-to-meter ratio
- Vehicle counting across entry and exit lines
- Simple and lightweight OpenCV implementation (no deep learning model)

## 📦 Tech Stack
- Python 3
- OpenCV
- NumPy

## 📸 Example
![Bird's Eye View](./birdseye_sample.png)

## 🎯 Purpose
This is a personal exploration project to understand the basics of traffic video analysis, perspective geometry, and real-world motion estimation using classical computer vision techniques.

---

Feel free to fork or contribute!
