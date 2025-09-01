# Arudino-Line-Follower

Design an Arduino-powered robot capable of executing precise square-shaped movements and accurately following a line using sensors.

A robotics project demonstrating **sensor-based navigation**, **custom PCB design**, and **C++ motor control programming** to achieve autonomous line-following behavior.

---

## 📌 Project Overview
This robot is designed to follow a black line on a white surface using **infrared (IR) sensors** for path detection. The control system is built on an **Arduino Uno**, with a **custom PCB** to handle power distribution, sensor input, and motor driver interfacing.

### Key Features
- **95% Path Accuracy** – Successfully follows a square track with minimal deviation.
- **Custom PCB** – Designed and soldered with 15+ components for reliable signal processing.
- **Optimized Motor Control** – Reduced error rates by 70% through calibration and refined C++ algorithms.

---

## 🛠️ Hardware Components
- **Arduino Uno** – Main microcontroller.
- **QRD1114 IR Sensors** – Detect line contrast.
- **L298N Motor Driver** – Controls DC motors.
- **DC Motors + Tires** – Provide movement.
- **Custom PCB** – Handles sensor inputs and motor driver connections.
- **Wooden Frame** – Provides mechanical stability.

---

## 🔧 Software & Firmware
- **Language**: C++
- **Development Environment**: Arduino IDE
- **Key Functions**:
  - Sensor calibration for precise line detection.
  - Proportional motor speed adjustment to maintain path accuracy.
  - Smooth directional changes at turns.

---

## ⚙️ How It Works
1. IR sensors detect the reflected light from the surface.
2. The microcontroller processes sensor input to determine line position.
3. Motor driver adjusts wheel speeds dynamically to keep the robot on track.

---

## 📸 Images & Media

Schematic to Follow: 
![IMG_2718.jpg](https://prod-files-secure.s3.us-west-2.amazonaws.com/c4db09fd-0464-4a21-9c87-26163a7f7f2d/d5b2f9bb-ec5e-4332-865a-34c29b056a03/IMG_2718.jpg)

Finished Arduino Line Follower Robot:

<img width="1206" height="1594" alt="IMG_6292" src="https://github.com/user-attachments/assets/56ea3f7d-778b-4c90-b7ef-7037db9d4d41" />

Bottom of Arduino Line Follower Robot:

<img width="1206" height="1584" alt="IMG_6293" src="https://github.com/user-attachments/assets/f0ad483c-097a-4cd9-86c6-af24425baea4" />


---

## 🚀 Future Improvements
- Add PID control for smoother navigation.
- Upgrade to LiPo batteries for longer runtime.
- Implement obstacle detection for enhanced autonomy.

---
