# 🔔 Smart Blind Stick – IoT-Based Assistive Project

## 📌 Overview
The **Smart Blind Stick** is an IoT-based assistive technology project designed to help visually impaired individuals navigate their environment safely. It uses ultrasonic sensors to detect nearby obstacles and alerts the user using a buzzer and an LED.

## 🚀 Features
- ✅ Obstacle detection using ultrasonic sensor (HC-SR04)
- ✅ Alerts with buzzer and LED when an obstacle is too close
- ✅ Real-time distance display via Serial Monitor
- ✅ Low-cost and compact implementation

## 🧠 Technologies Used
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Buzzer
- LED
- Jumper Wires
- Arduino IDE

## 🔌 Circuit Components and Connections

| Component        | Arduino Pin |
|------------------|-------------|
| Ultrasonic Trig  | D9          |
| Ultrasonic Echo  | D10         |
| Buzzer           | D11         |
| LED              | D13         |

## ⚙️ How It Works
1. The ultrasonic sensor emits sound waves and listens for their echo.
2. The time taken for the echo to return is used to calculate the distance.
3. If the obstacle is within a safety threshold (≤ 5 cm):
   - The buzzer sounds.
   - The LED lights up.
4. The measured distance is displayed on the Serial Monitor for debugging or real-time feedback.

## 💡 Applications
- Navigation aid for visually impaired individuals
- Proximity alert systems in smart canes or wheelchairs
- Obstacle avoidance in robotics

## 📎 Future Enhancements
- Integration with GPS and IoT for real-time tracking
- Voice-based alerts instead of buzzer
- Haptic/vibration feedback
- Mobile app to monitor distance remotely

## 🧪 Author & Credits
Developed as part of an academic IoT mini-project to explore low-cost assistive technologies.

---
