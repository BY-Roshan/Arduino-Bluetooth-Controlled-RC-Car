# 📱 Arduino Bluetooth Controlled RC Car

An Arduino-based robotic car controlled wirelessly from an Android smartphone via Bluetooth (HC-05 or HC-06 module).

---

## 🛠️ Hardware Requirements
* Arduino Uno
* L293D Motor Driver Shield (or standalone L293D / L298N module)
* HC-05 or HC-06 Bluetooth Module
* 2WD or 4WD Robotic Car Chassis with DC Motors
* External Battery Pack (7.4V / 9V)

---

## 📌 Pinout Connections
| Arduino Pin | Connected Component |
| :--- | :--- |
| **Pin 3** | Motor Left Forward (IN1) |
| **Pin 4** | Motor Left Backward (IN2) |
| **Pin 5** | Motor Right Forward (IN3) |
| **Pin 6** | Motor Right Backward (IN4) |
| **Pin 10** | Bluetooth TXD (SoftwareSerial RX) |
| **Pin 11** | Bluetooth RXD (SoftwareSerial TX) |
