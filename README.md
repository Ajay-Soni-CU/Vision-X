# 🚀 Vision-X — Mobile-Centric Edge AI Vision & Assistive Intelligence System 👁️🤖

Vision-X is a **real-time object detection and assistive vision system** designed around **mobile-first Edge AI principles**. It enables **on-device machine learning inference** using Android smartphones while supporting **external video streams** and **wearable sensor nodes**, all without relying on cloud services.

This project demonstrates a **complete, end-to-end applied Computer Vision pipeline** — spanning **hardware sensors, mobile ML deployment, decision logic, UI design, and system safety guarantees**.

---

## 📌 Project Identity

### Project Name
**Vision-X**

### Tagline
**Real-Time Object Detection Using Phone Camera and External Video Streams**

### Category
- Android Application
- Computer Vision
- Edge AI
- Assistive Technology
- On-Device Machine Learning

### Project Type
**Academic + Portfolio + Industry-Oriented System**

---

## 🌍 Core Vision

> **“Edge-first intelligence — private, offline, real-time, and human-centric.”**

Vision-X is built to prove that **powerful AI systems do not need the cloud**. By executing inference directly on mobile devices, the system ensures:

- Low latency
- High privacy
- Reduced power consumption
- Real-world deployability
- Assistive safety

---

## ❓ Problem Statement

Most existing object detection systems suffer from one or more of the following limitations:

- Heavy dependency on cloud infrastructure
- Single input source (only phone camera or only hardware)
- Poor suitability for real-time assistive use
- Lack of educational clarity in system design
- Overly complex deployment pipelines

These limitations make them unsuitable for:
- Edge AI learning
- Assistive applications
- Real-time demonstrations
- Academic evaluation

---

## ✅ Vision-X Solution Overview

Vision-X addresses these challenges by providing:

- **On-device inference using ONNX Runtime**
- **Dual input support** (Phone Camera + External Stream)
- **Modular Android architecture**
- **Edge-only intelligence execution**
- **Assistive-system-ready decision logic**
- **Fail-safe wearable integration**

---

## 🎯 Project Objectives

### Primary Objectives
- Build a real-time object detection Android application
- Deploy machine learning models efficiently on mobile devices
- Support multiple real-time video input sources
- Achieve smooth performance with minimal latency

### Secondary Objectives
- Provide a learning-friendly reference system
- Demonstrate Edge AI best practices
- Enable future hardware expansion
- Serve as a portfolio-grade industry project

---

## 👥 Target Users

### 🎓 Students
- Learn Android + ML integration
- Understand inference pipelines
- Study real-time data flow

### 👨‍💻 Developers
- Use as a base for Edge AI systems
- Extend with custom models
- Prototype assistive applications

### 🧑‍🏫 Faculty / Evaluators
- Evaluate architecture design
- Assess optimization techniques
- Judge applied ML implementation

### 🧑‍💼 Recruiters / Interviewers
- Assess real-world deployment skills
- Evaluate mobile ML understanding
- Review system-level thinking

---

## 🧠 High-Level System Architecture

Vision-X follows a **mobile-centric Edge AI architecture**:

- Wearable hardware performs **sensor capture only**
- Android device executes **all AI and decision logic**
- Data flows **one-directionally**
- No dependency on cloud services
- Fail-safe behavior built into hardware layer

---

## 🔄 End-to-End Data Flow

Sensor Input  
→ Frame Capture  
→ Preprocessing  
→ ONNX Model Inference  
→ Post-processing  
→ Decision Logic  
→ User Feedback (Visual / Audio)

---

## 🔍 Core Features

### 📱 Android Application
- Real-time object detection UI
- Bounding box overlay rendering
- Confidence score display
- Light and Dark theme support
- Optimized rendering pipeline

### 🎥 Dual Input Modes
#### 1️⃣ Phone Camera Mode
- Uses CameraX
- Live frame analysis
- Direct device camera access

#### 2️⃣ External Stream Mode
- MJPEG stream input
- Python / Jupyter-based streaming
- Flask server support

### 🧠 Machine Learning Inference
- ONNX Runtime for Android
- CPU-optimized inference
- Modular model loading
- Easy model replacement

### 🦯 Assistive System Logic
- Confidence-based alert triggering
- Distance-gated warnings
- Cooldown-based speech throttling
- Safety-first design

---

## 🧩 Wearable Hardware Philosophy

### Key Principle
> **No intelligence on wearable — sensor-only design**

### Benefits
- Lower power consumption
- Fail-safe operation
- No false alerts
- Extended battery life
- Simplified hardware logic

---

## 🔊 Audio Feedback System

- Text-to-Speech on Android
- Bone-conduction earphone support
- Ambient sound awareness
- Accessibility-compliant output

---

## 🛠 Technology Stack

### Programming Languages
- Java (Android)
- Python (Streaming server)

### Android SDK
- Minimum SDK: 24
- Target SDK: 36
- Compile SDK: 36

### Libraries & Tools
- CameraX
- ONNX Runtime
- Flask (Python)
- MJPEG Streaming
- Jupyter Notebook

---

## 🏗 Architecture Pattern

**MVC-inspired structure**

### Model
- ObjectDetector
- DetectionResult
- Inference pipeline

### View
- XML layout files
- Camera preview UI
- Overlay rendering

### Controller
- Activity classes
- User input handling
- Data orchestration

---

## 📂 Project Directory Structure

app/src/main/java/com/app/vision_x/

- MainActivity.java  
  Entry point, mode selection  

- PhoneModeActivity.java  
  Camera handling and inference  

- StreamModeActivity.java  
  External stream processing  

- JupyterCodeActivity.java  
  Displays Python streaming code  

- ObjectDetector.java  
  ONNX inference logic  

- DetectionResult.java  
  Detection data model  

- YuvToRgbConverter.java  
  Frame format conversion  

---

## 🧪 Core Functional Logic

### Key Methods
- ObjectDetector.detectObjects()
- YuvToRgbConverter.yuvToRgb()
- PhoneModeActivity.analyzeImage()

### Detection Pipeline
Input Frame  
→ Preprocessing  
→ Model Inference  
→ Post-processing  
→ Overlay Rendering  

---

## ⚡ Performance Optimizations

- Background threading for inference
- Efficient frame reuse
- Controlled FPS detection
- Camera lifecycle optimization
- Memory-safe bitmap handling

---

## 🔋 Battery & Network Optimization

- Camera active only when visible
- Streams closed on activity destroy
- No background services
- No unnecessary network usage

---

## 🔐 Security & Privacy

- Minimal permissions
- No cloud communication
- No image storage
- User-controlled streams
- Offline-first execution

---

## ⚠️ Limitations

- Performance depends on device hardware
- External stream quality affects accuracy
- Model accuracy depends on training data

---

## 🚀 Future Enhancements

- GPU / NNAPI acceleration
- Object tracking
- Multi-stream input
- Detection recording
- Advanced analytics

---

## 🏁 Conclusion

Vision-X is a **complete, real-world Edge AI system**, showcasing:

- Mobile ML deployment
- Hardware-aware design
- Assistive intelligence principles
- Clean Android architecture
- Industry-relevant problem solving

This project stands **far above typical academic implementations** and reflects **production-level system thinking**.

---

## 👨‍💻 Author

**Ajay Soni**  
BCA (Hons.) Data Science  
Chandigarh University, Unnao  

📧 Email: programmingwithcode@gmail.com  
🔗 LinkedIn: linkedin.com/in/ajay-soni-cu  

⭐ *Vision-X — Turning mobile devices into intelligent vision systems.*
