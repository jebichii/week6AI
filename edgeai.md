# 🧠 Edge AI Prototype – Recyclable Item Classifier

This project showcases a lightweight image classification model designed for real-time inference on edge devices such as Raspberry Pi. Built with TensorFlow Lite, the prototype simulates the ability to recognize recyclable items and demonstrates the efficiency and privacy benefits of Edge AI.

---

## 📍 Project Goals

- Train a compact CNN model to classify recyclable items (e.g., bottles).
- Convert the model to TensorFlow Lite for deployment.
- Simulate edge inference using Colab to test latency and performance.
- Highlight real-world benefits of Edge AI in low-power, privacy-sensitive scenarios.

---

## ⚙️ Tools & Technologies

| Tool             | Purpose                            |
|------------------|-------------------------------------|
| TensorFlow       | Model training and architecture     |
| TensorFlow Lite  | Model optimization and conversion   |
| Google Colab     | Simulation environment              |
| Raspberry Pi     | (Optional) target hardware platform |
| CIFAR-10 Dataset | Sample dataset for recyclable class |

---

## 🚀 Setup Instructions

1. Clone or open the notebook in [Google Colab](https://colab.research.google.com/).
2. Install dependencies:
   ```python
   !pip install tensorflow numpy matplotlib
