# 🧠 Intelligent Vehicle & Ambulance Detection Dataset

## Team : [Techiee]

### 🚗🚑 Object Detection Training Dataset for Smart Traffic Systems

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Toolkit](https://img.shields.io/badge/OIDv4-Toolkit-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

---

Welcome to the **Vehicle & Ambulance Detection Dataset**! This dataset is curated to train and test object detection models focused on differentiating between various vehicle types, including **ambulances**, making it highly relevant for **autonomous vehicles**, **emergency response systems**, and **traffic monitoring solutions**.

---

## 🚀 Problem Statement

### Objective

Develop and evaluate object detection models that can:

1. 🚌 **Differentiate between multiple vehicle types** – car, bus, motorcycle, ambulance, and truck.
2. 🧠 **Train specialized models** – e.g., an ambulance-specific detector.
3. ✅ **Test detection models** on scenes with high vehicle density.
4. 📍 **Use in smart city and autonomous driving applications.**

---

## 🎯 Use Cases

- 🚘 **Train object detectors** for vehicle classification.
- 🚓 **Ambulance detection system** for emergency response prioritization.
- 🚦 **Autonomous vehicle vision system** training data.
- 🔍 **Dataset quality analysis** for Open Images usage exploration.
- 📊 **Benchmarking object detection models** on real-world traffic scenes.

---

## 🗃️ Dataset Overview

### 📁 Dataset Source
This dataset was gathered using the **OIDv4 Toolkit**, allowing flexible class-based image retrieval from the **Open Images Dataset** with bounding box annotations.

### 📷 Example Images
![Example1](./images/image1.png)
![Example2](./images/image2.png)
![Example3](./images/image3.png)

> Includes bounding boxes for: `Car`, `Truck`, `Motorcycle`, `Bus`, and `Ambulance`.

---

## ⚙️ Tools Used

- 🛠 **OIDv4 Toolkit** for class-wise image downloading.
- 💡 **Open Images Dataset** (V6) – a large-scale dataset with rich annotations.
- 🐍 Python 3.x
- 📦 Libraries: `pandas`, `opencv-python`, `matplotlib`, `scikit-learn` (for preprocessing/visualization)

---

## 🧰 Getting Started

### Prerequisites

- Python 3.8+
- Required libraries (see `requirements.txt`):
  ```bash
  pip install -r requirements.txt
  ```

### Installation

```bash
git clone https://github.com/yourusername/vehicle-amb-detection-dataset.git
cd vehicle-amb-detection-dataset
```

---

## 📁 Folder Structure

```plaintext
vehicle-amb-detection-dataset/
│
├── images/               # Example image samples
├── annotations/          # Bounding box CSVs
├── utils/                # Toolkit scripts & download helpers
├── requirements.txt
└── README.md
```

---

## 🧠 Algorithm Suggestion

> You can train your own object detector using:

- 📍 Feature Extractors: YOLOv5, SSD, Faster R-CNN
- 🧠 Models: PyTorch, TensorFlow
- 🎯 Training Approach:
  - Parse OID bounding boxes
  - Format in YOLO/COCO style
  - Train using fine-tuned parameters for multi-class detection

---

## 🤝 Contributing

We welcome contributions to extend this dataset (e.g., more vehicle types, more regions). Please fork the repo, make changes, and submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙌 Acknowledgments

This dataset is inspired by the need for precise object detection in high-stakes environments such as autonomous driving and emergency services. Special thanks to the creators of the **OIDv4 Toolkit** and **Open Images Dataset** for enabling scalable, real-world data access.
