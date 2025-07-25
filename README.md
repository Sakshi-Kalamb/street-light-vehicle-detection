# 🚦 Street Light Control System Using Vehicle Detection

An Arduino-based project where a street light automatically turns ON or OFF based on the presence of a vehicle, using an LDR sensor.

## 💡 Features

- Detects ambient light intensity using LDR.
- Automatically switches light ON when it’s dark.
- Efficient use of power—light stays OFF in bright conditions.
- Useful for smart street lighting systems.

## 🔧 Technologies Used

- Arduino UNO
- LDR (Light Dependent Resistor)
- LED or street light module
- C++ (Arduino language)

## 📸 Screenshot

![Street Light Project](https://raw.githubusercontent.com/Sakshi-Kalamb/street-light-vehicle-detection/refs/heads/main/project.png)

## 🧠 Working Principle

- The LDR senses the amount of ambient light.
- When the light level falls below a threshold (e.g., during night or vehicle shadow), the Arduino switches ON the street light.
- Otherwise, the light stays OFF during the day.

## 🔌 How to Run

1. Connect the LDR to analog pin A0, and LED to pin 13.
2. Upload the code to your Arduino using Arduino IDE.
3. Observe how the light turns ON in darkness and OFF in brightness.

## ✍️ Project Inspiration

Created as part of an IoT workshop to demonstrate real-time automation using sensors with Arduino.

