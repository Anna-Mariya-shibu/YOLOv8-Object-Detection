# YOLOv8-Object-Detection



## Real-Time Image-Based Object Detection using YOLOv8

---

## 📌 Repository Description

This repository contains a beginner-level micro project for performing real-time object detection using the YOLOv8 deep learning model in Python.

The project demonstrates how a pre-trained YOLOv8 model can be used to detect multiple objects from an input image and visualize the results using bounding boxes, class labels and confidence scores.

The implementation is designed to be simple and suitable for students who are new to computer vision and deep learning.

---

## 📝 Project Overview

This micro project shows how to apply modern object detection techniques using the YOLOv8 model.

An image provided by the user is processed by the trained network and all detected objects are displayed with:

* bounding boxes
* class names
* confidence values

The main aim of this project is to give hands-on experience with object detection workflows and inference using pre-trained models.

---

## ✨ Key Features

* Uses pre-trained YOLOv8 model
* Easy and beginner-friendly implementation
* Supports image input in Google Colab
* Detects multiple objects in a single image
* Displays bounding boxes, labels and confidence scores
* Adjustable detection confidence threshold
* Lightweight and fast inference using YOLOv8 Nano model

---

## 🛠️ Technologies & Libraries

* Python
* Ultralytics YOLOv8
* OpenCV
* NumPy
* Google Colab

---

## 📁 Project Structure

```
Object-Detection-YOLOv8-Micro-Project
│
├── Untitled24.ipynb
└── README.md
```

---

## ⚙️ Installation

Install the required package in Google Colab using:

```
pip install ultralytics
```

---

## ▶️ How to Run the Project

1. Open the notebook file:

```
Untitled24.ipynb
```

in Google Colab.

2. Install the YOLOv8 library:

```
!pip install ultralytics
```

3. Upload an image file:

```python
from google.colab import files
files.upload()
```

4. Load the YOLOv8 model and perform detection:

```python
from ultralytics import YOLO

model = YOLO("yolov8n.pt")

results = model("your_image.jpg", conf=0.4)
```

5. The output image with detected objects will be displayed automatically.

---

## 📊 Output Description

The output of the system includes:

* rectangular bounding boxes around detected objects
* predicted class labels
* confidence scores for each detection

---

## 🎯 Use Cases

* Learning deep learning–based object detection
* Mini projects for computer vision courses
* Academic demonstrations
* Image analysis systems
* Prototype development for vision-based applications

---

## 🚀 Future Improvements

The following enhancements can be added in the next phase of the project:

* Integrate the detection module into a Django web application
* Add real-time webcam and video stream detection
* Run the project locally using VS Code or PyCharm
* Allow saving detection results automatically
* Support custom dataset training
* Add a simple web user interface for image upload

---

## 👩‍💻 Author

**Anna Mariya Shibu**

This project is developed as a beginner micro project to understand the practical implementation of modern object detection using deep learning.
