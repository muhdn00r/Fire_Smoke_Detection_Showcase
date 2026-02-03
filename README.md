# Real-Time Fire & Smoke Detection System 🔥

> **Visual Showcase / Portfolio Demo**
> *Note: This repository serves as a visual documentation of my Computer Vision project. The specific training weights and source code are proprietary.*

## 🎥 Project Demo

https://github.com/user-attachments/assets/5c29d32e-ac32-4639-90bf-8a9328dfcbfa

---

## 🚀 Overview
An edge-optimized Computer Vision application designed to detect early signs of fire and smoke in real-time video feeds. This project focused on balancing high detection accuracy with the low-latency requirements of embedded/mobile deployment.

### Core Problem
Traditional smoke detectors are passive and slow to react in large open spaces (e.g., warehouses, forests). Visual detection offers faster response times but often requires heavy GPU resources that are not feasible for remote deployment.

### The Solution
I developed a lightweight detection pipeline that:
1.  **Detects:** Identifies "Fire" and "Smoke" classes with high confidence using deep learning.
2.  **Optimizes:** Tuned for inference speed on resource-constrained environments (mobile/edge).
3.  **Alerts:** Capable of triggering immediate visual warnings upon detection.

## 🛠️ Tech Stack
*   **Core Logic:** Python, OpenCV
*   **AI Models:** YOLO (You Only Look Once), TensorFlow
*   **Deployment:** Optimized for Mobile/Edge inference
*   **Training:** Custom dataset curation and annotation for hazard environments.

## 🏆 Key Engineering Challenges
*   **False Positive Reduction:** Tuned confidence thresholds to distinguish between actual smoke and similar visual patterns (e.g., fog, steam).
*   **Latency Optimization:** Achieved real-time frame rates (FPS) suitable for continuous monitoring without lag.
*   **Data Engineering:** Manually annotated diverse datasets to improve model robustness under different lighting conditions.

---
© 2026 Muhammad Noor Bin Nor Affandi | Computer Engineering @ UTeM
