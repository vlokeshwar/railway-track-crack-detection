🚆 AI-Based Railway Track Crack Detection Robot using YOLOv5

📌 Overview

This project presents an autonomous railway track inspection system that detects cracks in real-time using deep learning and embedded systems. The system combines an ESP32-based robotic platform with a Raspberry Pi running YOLOv5 to ensure accurate and efficient defect detection.

🎯 Features

✅ Real-time crack detection using YOLOv5

✅ Achieves 91.4% mAP@0.5

✅ Runs at 15–20 FPS on Raspberry Pi
✅ Dual-controller architecture (ESP32 + Raspberry Pi)
✅ IR sensor-based pre-detection for efficiency
✅ GPS-based location tracking
✅ GSM-based alert system
✅ Fully working hardware prototype

🏗️ System Architecture
ESP32 controls robot movement and sensor input
IR sensor detects possible anomalies
Raspberry Pi performs image-based crack detection
GPS provides location coordinates
GSM sends alert messages


⚙️ Hardware Components
ESP32 Microcontroller
Raspberry Pi 4 Model B
IR Sensor
Camera Module
GPS Module
GSM Module (SIM800L)
Motor Driver + DC Motors



💻 Software & Tools
Python
YOLOv5
OpenCV
Roboflow (Dataset + Annotation)
Arduino IDE

📂 Dataset
Source: Roboflow Railway Crack Detection Dataset
Total Images: 1,869
Image Size: 416×416
Classes: railway-gap

🧠 Model Training
Model: YOLOv5s
Epochs: 30
Batch Size: 4
Input Size: 416×416
mAP@0.5: 91.4%



📊 Results
Real-time detection at 15–20 FPS
Accurate crack detection with minimal false positives
Works under varying lighting and surface conditions



🚀 How It Works
Robot moves along railway track
IR sensor detects anomaly
Raspberry Pi captures image
YOLOv5 detects crack
GPS fetches location
GSM sends alert

🔮 Future Improvements
Solar-powered system 🌞
Cloud-based monitoring dashboard
Multi-defect detection
Edge AI optimization


📎 Applications
Railway safety monitoring
Preventive maintenance
Smart transportation systems

⭐ If you like this project

Give it a ⭐ 
