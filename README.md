# 🚁 Real-Time Face Detection and Tracking Drone using CNN & YOLO

![YOLOv5](https://img.shields.io/badge/YOLOv5-Object%20Detection-red) ![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-blue) ![Jetson Nano](https://img.shields.io/badge/Jetson%20Nano-Edge%20AI-green)

This project demonstrates a **real-time face detection and tracking system** integrated into a drone’s navigation system. It leverages **CNN-based models** and **YOLOv5** for detection, with **OpenCV** managing live video processing. The system is deployed on an **NVIDIA Jetson Nano**, optimized for efficient real-time computation.

---

## 🎯 Project Overview

The goal is to enable a drone to **detect, track, and follow human faces** autonomously. Preliminary testing under controlled indoor environments shows **high detection accuracy** and **smooth movement tracking**.

### 🔹 Key Highlights

* ⚡ Real-time detection using **YOLOv5** and **CNN models**
* 🧭 Integrated drone control for autonomous navigation
* 🧠 Edge AI implementation on **Jetson Nano**
* 🧩 Modular system for easy future integration (GPS, sensors, etc.)

---

## 📊 Project Progress

### ✅ Completed

* Integration of **YOLOv5** and **CNN-based detection models**
* Successful **real-time tracking** in indoor environments
* Smooth tracking verified using **OpenCV**

### 🔄 Next Steps

* Improve model tuning for dynamic outdoor conditions
* Add **obstacle avoidance** and **GPS-based navigation**
* Test under **variable lighting** and **motion patterns**

---

## 🧠 Technology Stack

| Component              | Technology Used                       |
| ---------------------- | ------------------------------------- |
| **Face Detection**     | YOLOv5, CNN-based models              |
| **Video Processing**   | OpenCV                                |
| **Hardware**           | NVIDIA Jetson Nano                    |
| **Control System**     | DroneKit / Python Scripts             |
| **Planned Extensions** | GPS module, LiDAR, Ultrasonic sensors |

---

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.8+
* NVIDIA Jetson Nano / Linux system
* PyTorch and OpenCV
* Drone SDK (e.g., DroneKit)

### Steps

```bash
# Clone the repository
git clone https://github.com/<your-username>/face-detection-drone.git
cd face-detection-drone

# Install dependencies
pip install -r requirements.txt

# Run main script
python main.py
```

---

## 🎥 Demo

> Add drone test videos or demo GIFs here (e.g., YouTube link)

---

## 🚧 Future Enhancements

* 🔁 Multi-face tracking support
* 🛰️ GPS-based autonomous flight
* 🚧 Real-time obstacle avoidance
* 🌗 Low-light condition optimization

---

## 👨‍💻 Contributors

* **Vishvas Patel** – Project Lead & Developer

💡 Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌐 Contact

📧 Email: **[vishvaskumar.patel@example.com](mailto:vishvaskumar.patel@example.com)**
🔗 LinkedIn: [Vishvas Patel](https://linkedin.com/in/vishvaspatel)

---

## 📝 GitHub Description

A drone-based real-time **face detection and tracking system** using **CNN and YOLOv5** integrated with **OpenCV** on **NVIDIA Jetson Nano**. Designed for smooth, accurate tracking with upcoming support for **GPS navigation** and **obstacle avoidance**.
