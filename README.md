# 🐑 BhedChaal — AI-Powered Crowd Management

BhedChaal is an AI and computer-vision system designed to monitor crowd density, identify unusual behavior, and support safer management of large gatherings.

## 🚀 Features

- 🎥 Crowd density estimation using CSRNet
- 👥 Real-time face detection with YOLOv11-Face
- 🧠 Crowd anomaly detection
- 🗺️ Homography transformation for top-view mapping
- 🎮 Physics-based crowd movement simulation
- 🖼️ Real-ESRGAN image enhancement
- 📲 Camera-based web interface

## 🎯 Potential Use Cases

- Large public gatherings and festivals
- Stadiums and college events
- Railway stations and airports
- Disaster-management scenarios
- Rallies and high-density venues

## 🏗️ Architecture

```text
Camera Feed
    ↓
YOLOv11-Face + Crowd Density Model
    ↓
Anomaly Detection
    ↓
Homography + Movement Simulation
    ↓
Dashboard + Alerts
```

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Flask |
| Computer Vision | YOLOv11-Face, OpenCV |
| Crowd Estimation | CSRNet |
| Enhancement | Real-ESRGAN |
| Simulation | Physics-based modeling |

## 👨‍💻 Author

Built by **Neetesh Sharma**.
