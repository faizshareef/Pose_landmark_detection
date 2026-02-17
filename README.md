

# 🧍 Pose Landmark Detection from Static Images using MediaPipe


## 📌 Project Overview 

This project implements human pose landmark detection from a static input image using MediaPipe Pose and OpenCV. The system detects 33 anatomical body keypoints and visualizes skeletal connections directly on the image.

The application processes a single image, performs pose inference using MediaPipe’s pre-trained pose model, and renders landmark overlays representing the detected human posture.

This project demonstrates fundamental computer vision techniques including image preprocessing, landmark extraction, and skeletal visualization.

---

## 🚀 Features

- Detects 33 human body landmarks
- Static image pose estimation
- Skeletal landmark visualization
- CPU-based inference (no GPU required)
- Lightweight and efficient implementation

---

## 🛠️ Tech Stack

- **Programming Language:** Python 3.10  
- **Pose Estimation Framework:** MediaPipe Pose  
- **Computer Vision Library:** OpenCV  
- **Numerical Computation:** NumPy  
- **Version Control:** Git & GitHub  

---

## 🧠 How It Works

1. Loads input image using OpenCV.
2. Converts image from BGR to RGB format.
3. Processes the image using MediaPipe Pose model.
4. Extracts 33 body landmarks.
5. Draws skeletal connections on the image.
6. Displays final pose visualization.

---

## OUTPUT IMAGES:
<img width="800" height="690" alt="output_1" src="https://github.com/user-attachments/assets/26c0a79f-e152-4436-8e63-4e59c141ddcd" />

<img width="794" height="678" alt="output_2" src="https://github.com/user-attachments/assets/be0fb0ad-ca14-4df8-ac1d-6f6e69b3570b" />

## 📈 Future Improvements

1. Add joint angle calculation
2. Integrate exercise form analysis
3. Extend to real-time webcam processing
4. Add action classification module
