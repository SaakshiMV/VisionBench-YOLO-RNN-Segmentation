# 🚀 VisionBench: YOLO, RNN & Segmentation Evaluation

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Domain](https://img.shields.io/badge/Computer%20Vision-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

> A structured benchmarking project comparing object detection, sequential modeling, and pixel-level segmentation approaches in computer vision.

This project evaluates three different paradigms:

- 🔍 **YOLO** → Real-time Object Detection  
- 🔁 **RNN** → Sequential/Temporal Modeling  
- 🎨 **Semantic Segmentation** → Pixel-level Classification  

The goal is to compare their performance, strengths, and limitations using standard evaluation metrics.

---

## 🧠 Models Covered

- YOLO (You Only Look Once)
- RNN-based models
- Semantic Segmentation models

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision & Recall  
- IoU (Intersection over Union)  
- Loss Curves  

---

## 📊 Model Comparison

| Model | Task | Strengths | Weaknesses |
|------|------|----------|------------|
| YOLO | Object Detection | Fast, real-time | Less precise boundaries |
| RNN | Sequential Modeling | Captures temporal patterns | Not ideal for images alone |
| Segmentation | Pixel Classification | High precision | Computationally expensive |

---

## 🧠 Key Insights

- YOLO performs best in real-time detection tasks but struggles with fine boundaries.
- Semantic segmentation provides the highest spatial accuracy.
- RNNs are useful when temporal dependencies are involved.
- There is a trade-off between speed and precision across models.

---

## 🏗️ Project Structure

```

visionbench/
│
├── notebooks/
│   └── evaluation_yolo_rnn_segmentation.ipynb
│
├── results/
│   ├── images/
│   └── graphs/
│
├── src/
├── README.md
├── requirements.txt
└── .gitignore

````

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/visionbench.git
cd visionbench
pip install -r requirements.txt
jupyter notebook
````

---

## 🔮 Future Work

* Add real-time inference
* Deploy using Streamlit
* Improve model optimization
* Expand dataset for robustness

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome!

---

## ⭐ Acknowledgements

Inspired by modern computer vision research and benchmarking practices.
