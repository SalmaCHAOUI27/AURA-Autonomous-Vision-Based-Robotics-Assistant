# AURA-Autonomous-Vision-Based-Robotics-Assistant

# 🤖 AURA — Autonomous Vision-Based Robotics Assistant

## 📌 Overview

**AURA** is an autonomous mobile robot designed to perceive its environment, make decisions, and move independently. The project integrates **robotics, embedded systems, and computer vision** using a modular and scalable architecture suitable for real-world applications.

AURA combines real-time sensor data, visual perception, and control algorithms to perform autonomous navigation tasks such as line following and obstacle avoidance.

---

## 🎯 Objectives

* Design and build an autonomous robotic system from scratch
* Integrate hardware and software components in a real-world setup
* Implement line following and obstacle avoidance behaviors
* Apply basic computer vision techniques for environment perception
* Develop clean, modular, and well-documented code for a professional portfolio

---

## 🧠 System Architecture

AURA uses a **hybrid control architecture**:

### 🔹 Arduino (Low-Level Control)

* Motor control (PWM, direction control)
* Ultrasonic sensor data acquisition
* Real-time movement execution
* Serial communication with Raspberry Pi

### 🔹 Raspberry Pi (High-Level Control)

* Camera input processing
* Computer vision algorithms
* Decision-making logic
* Command transmission to Arduino

---

## 🛠️ Tools & Technologies

### Hardware

* Raspberry Pi (3/4)
* Arduino Uno / Nano
* DC Motors + Motor Driver (L298N or equivalent)
* Ultrasonic Sensor (HC-SR04)
* USB Camera / Camera Module
* Robot chassis, wheels, battery pack

### Software

* **Python** (vision processing & high-level logic)
* **C / C++** (Arduino firmware)
* **OpenCV** (computer vision)
* **UART Serial Communication**
* **Raspberry Pi OS (Linux)**

### Development Tools

* VS Code
* Arduino IDE
* Git & GitHub

---

## ⚙️ Implementation Steps

### 1️⃣ Hardware Assembly

* Assemble the robot chassis
* Mount motors, wheels, camera, and sensors
* Connect motors to motor driver
* Set up power distribution
* Connect Arduino to Raspberry Pi

### 2️⃣ Motor Control

* Implement forward, backward, left, and right movement
* Speed control using PWM
* Calibrate motors for smooth navigation

### 3️⃣ Line Following

* Capture video frames from the camera
* Apply image preprocessing (grayscale, blur, threshold)
* Detect the line position
* Adjust motor speeds based on line offset (PID optional)

### 4️⃣ Obstacle Detection & Avoidance

* Measure distance using ultrasonic sensor
* Define safety distance thresholds
* Implement avoidance logic (stop, turn, resume path)

### 5️⃣ Computer Vision Module

* Real-time video stream processing
* Color and shape detection
* Simple sign recognition (e.g., STOP marker)
* Decision output based on visual data

### 6️⃣ Arduino ↔ Raspberry Pi Communication

* Serial protocol design
* Sensor data transmission to Raspberry Pi
* Motion command transmission to Arduino
* Error handling and synchronization

### 7️⃣ Integration & Testing

* Integrate all modules
* Test in different environments
* Tune parameters (speed, thresholds)
* Debug and optimize performance

---

## 🧪 Testing & Validation

* Unit testing for each module
* Navigation testing in real environments
* Obstacle stress testing
* Vision accuracy tests under varying lighting conditions

---

## 🚀 Possible Extensions

* Web-based control dashboard
* Mobile application control
* Voice commands
* SLAM (Simultaneous Localization and Mapping)
* Object detection using lightweight ML models
* Autonomous parking behavior

---

## 🏁 Expected Outcomes

* Fully autonomous navigation
* Real-time obstacle avoidance
* Vision-based decision making
* Demonstration of robotics and AI fundamentals

---

## 🌍 Portfolio Value

This project demonstrates:

* End-to-end robotics system design
* Hardware–software co-design
* Real-time decision making
* Practical application of computer vision

> **AURA** is not just a robot — it is the bridge between code and the physical world.

---

## 📷 Demo

*(Add images and videos of the robot in action here)*
