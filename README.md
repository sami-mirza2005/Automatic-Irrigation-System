# 🌱 Automatic Irrigation System Using Arduino Nano

An Arduino Nano-based Automatic Irrigation System that monitors soil moisture and automatically controls a water pump to reduce water wastage and minimize manual effort.

---

## 📖 Overview

This project uses an Arduino Nano and a soil moisture sensor to automate irrigation. When the soil becomes dry, the system automatically turns the water pump ON. Once sufficient moisture is detected, the pump turns OFF.

---

## ✨ Features

* Automatic soil moisture monitoring
* Automatic water pump control
* 16×2 I2C LCD status display
* Buzzer alert
* Water-saving automation
* Simple and low-cost design

---

## 🛠 Components Used

* Arduino Nano
* Soil Moisture Sensor
* Relay Module
* Water Pump
* 16×2 I2C LCD
* Buzzer
* Jumper Wires
* Power Supply

---

# 📷 Project Gallery

## 🌿 Final Project

![Decorated Project](Images/decorated_project.jpg)

---

## 🔌 Circuit Model

![Circuit Model](Images/circuit_model.jpg)

---

## 💧 Wet Soil Condition

LCD Output:

* **Status:** WET
* **Pump:** OFF

**LCD Display**

![Wet LCD](Images/wet_lcd.jpg)

**Project Condition**

![Wet Condition](Images/wet_condition.jpg)

---

## ☀️ Dry Soil Condition

LCD Output:

* **Status:** DRY
* **Pump:** ON

**LCD Display**

![Dry LCD](Images/dry_lcd.jpg)

**Project Condition**

![Dry Condition](Images/dry_condition.jpg)

---

## ⚙️ Working Principle

1. Read soil moisture using the sensor.
2. If the soil is **WET**, keep the pump **OFF**.
3. If the soil is **DRY**, turn the pump **ON**.
4. Display the current status on the LCD.
5. Repeat the process continuously.

---

## 📂 Folder Structure

```text
Automatic-Irrigation-System-Arduino/
│
├── Arduino_Code/
│   └── Automatic_Irrigation_System.ino
│
├── Images/
│   ├── decorated_project.jpg
│   ├── circuit_model.jpg
│   ├── wet_lcd.jpg
│   ├── wet_condition.jpg
│   ├── dry_lcd.jpg
│   └── dry_condition.jpg
│
└── README.md
```

---

## 👥 Team

**Team Name:** Eternal Voltage

* Md. Abdullah Al Sami Mirza
* Joyosree Roy Joya
* Puja Banik Trina
* Abdul Hamid
* Fahim Ahmed
* Samia Jannat Ahana

---

## 🙏 Acknowledgements

Special thanks to **Tonmoy Sir** for his valuable guidance and support throughout this project.

---

## 📄 License

This project was developed for academic and educational purposes.

