# Fall Detection System using Raspberry Pi, NCNN & Meta API

An AI-powered Fall Detection System that performs real-time fall detection using an optimized deep learning model deployed on a Raspberry Pi. The system leverages the NCNN framework for fast inference and low memory consumption, making it suitable for resource-constrained embedded devices. When a fall is detected, emergency notifications are instantly sent to registered contacts using the Meta API and WhatsApp Business API. The project also supports GSM (SIM800L)-based SMS alerts as an alternative communication method.

---

##  Overview

Falls are one of the leading causes of severe injuries among elderly individuals and people with medical conditions. Delayed assistance after a fall can result in serious health complications. This project provides an intelligent and cost-effective solution by combining deep learning, computer vision, embedded systems, and cloud communication to detect falls in real time and notify caregivers immediately.

The deep learning model is optimized using the NCNN framework, enabling efficient deployment on Raspberry Pi while maintaining high accuracy and low inference latency.

---

##  Features

-  Real-time fall detection using live camera feed
-  Deep learning-based human fall recognition
-  NCNN optimized model for Raspberry Pi
-  ONNX model conversion and optimization
-  Instant WhatsApp alerts using Meta API
-  GSM (SIM800L) SMS alert support
-  Fast inference with low memory usage
-  Real-time prediction logging
-  Designed for low-power embedded systems
-  Suitable for elderly care, hospitals, and smart healthcare

---

##  Technologies Used

- Python
- Raspberry Pi
- OpenCV
- Deep Learning
- ONNX
- NCNN Framework
- Meta API
- WhatsApp Business API
- GSM Module (SIM800L)
- UART Communication

---

## System Workflow

1. Capture live video using Raspberry Pi camera.
2. Load the optimized NCNN model.
3. Perform real-time inference.
4. Detect whether a fall has occurred.
5. Trigger the alert system.
6. Send WhatsApp notification through Meta API.
7. (Optional) Send SMS alert using GSM module.
8. Display and log prediction results.

---

##  Project Structure

```
Fall-Detection-System/
│
├── dataset/
├── model/
├── ncnn_model/
├── scripts/
├── images/
├── requirements.txt
├── README.md
└── main.py
```

---

##  Model Optimization

The original deep learning model is:

- Exported to ONNX format
- Converted to NCNN
- Quantized using FP16/INT8
- Optimized for Raspberry Pi deployment

This significantly reduces model size, improves inference speed, and lowers memory usage while maintaining high detection accuracy.

---

##  Alert System

### Meta API + WhatsApp API

- Instant WhatsApp notifications
- Internet-based communication
- Supports multimedia alerts
- Faster and more reliable than SMS
- Easily scalable

### GSM Module (SIM800L)

- SMS-based emergency notifications
- Works without internet
- Suitable for remote locations

---

##  Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/Fall-Detection-System.git
cd Fall-Detection-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python main.py
```

---

##  Applications

- Elderly care monitoring
- Hospitals
- Assisted living facilities
- Smart homes
- Healthcare IoT
- Rehabilitation centers

---

##  Future Improvements

- Mobile application integration
- Cloud dashboard for monitoring
- GPS location sharing
- Voice call alerts
- Multiple camera support
- Fall severity estimation
- Patient health monitoring integration

---


---

