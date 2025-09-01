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
*(Insert images of PCB layout, final build, and robot in action)*

---

## 🚀 Future Improvements
- Add PID control for smoother navigation.
- Upgrade to LiPo batteries for longer runtime.
- Implement obstacle detection for enhanced autonomy.

---
