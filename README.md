# E-Bike Traction Control & Wheel Slip Detection

This project implements a basic traction control system for e-bikes using dual wheel speed sensors. By comparing front and rear wheel speeds, the controller detects rear-wheel slip and dynamically limits motor torque through PWM control to improve traction on wet or low-grip surfaces.

## Features
- Dual wheel speed sensing (front and rear)
- Slip ratio calculation for traction detection
- Dynamic PWM torque limiting
- Improves stability and rider safety on low-traction roads

## Hardware Required
- Arduino board
- 2x Hall-effect wheel speed sensors
- Motor driver with PWM input
- Proper power isolation and wiring

## Notes
- This is a prototype control strategy for educational purposes.
- Real traction control uses high-rate sensors and closed-loop motor controllers.

---

👨‍💻 **Author:** K.Viswanadh
