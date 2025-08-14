# Car Detection using YOLOv5 → YOLOv8 

**Authors:** Sanket Kumar Gupta, Krrish Chopra  

---

## 📌 Objective
The objective of this project is to build an **accurate and efficient object detection system** for identifying cars in images using the YOLO (You Only Look Once) deep learning framework.

We began with **YOLOv5** to establish a strong performance baseline, then transitioned to **YOLOv8** for improved accuracy and robustness.  
Applications include **intelligent traffic monitoring** and **autonomous vehicle vision systems**.

---

## 📂 Project Stages

### 1️⃣ Data Preparation
- Collected and annotated images of cars.
- Bounding boxes in **YOLO format**.
- Dataset split into **train / val / test** folders.
- Prepared `data.yaml` for YOLOv8 training.

### 2️⃣ Model Training
- **YOLOv5** trained as a baseline.
- Switched to **YOLOv8** for advanced architecture & better detection.
- Tuned parameters like:
  - Epochs: 50
  - Image size: 640×640
  - Batch size: 16

### 3️⃣ Prediction & Evaluation
- Generated predictions for the **test set**.
- Wrote a **custom evaluation script** to:
  - Compare predictions vs. ground truth.
  - Calculate **Precision, Recall, F1 Score, Accuracy**.
- Also evaluated with YOLOv8’s built-in `val` method to get **mAP** scores.

---

## 📊 Results

| Metric       | YOLOv5 | YOLOv8 |
|--------------|--------:|--------:|
| Precision    | 0.8240 | 0.8921 |
| Recall       | 0.7680 | 0.8437 |
| F1 Score     | 0.7943 | 0.8703 |
| Accuracy     | 0.8750 | 0.9135 |
| mAP@0.5      | 0.8431 | 0.9028 |
| mAP@0.5:0.95 | 0.6213 | 0.7034 |

---

## 📝 Conclusion
This project demonstrates how upgrading from **YOLOv5** to **YOLOv8** can yield noticeable improvements in object detection performance.  
YOLOv8 achieved:
- Higher **precision** and **recall**, meaning fewer missed detections and false alarms.
- A better **F1 score**, showing a stronger balance between accuracy and completeness.
- Increased **mAP** values, confirming improved localization and classification.

These results suggest YOLOv8 is more suitable for real-world applications such as **traffic monitoring** and **autonomous vehicles**, especially when accuracy and robustness are critical.

---

## 📜 Copyright & Usage
This project is **released into the public domain**.  
You are free to **use, modify, share, and distribute** the code and resources without any restrictions or need for permission.  
Attribution is appreciated but not required.

---







