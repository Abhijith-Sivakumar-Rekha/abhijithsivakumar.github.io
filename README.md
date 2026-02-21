# abhijithsivakumar.github.io
# ☀️ DIY Smart Solar Tracking Station
Built with the Keyestudio KS0530 Kit and Arduino UNO.

## 📋 Project Overview
This project creates a dual-axis solar tracker that follows the sun to maximize energy efficiency. It also monitors environmental data like light intensity (Lux), temperature, and humidity.

## 🛠 Hardware Used
- **Microcontroller:** Keyestudio UNO
- **Motors:** 2x 9g Servos (Horizontal/Vertical)
- **Sensors:** 4x Photoresistors, DHT11 (Temp/Hum), BH1750 (Light)
- **Display:** I2C 1602 LCD

## 📂 Repository Structure
- `/Code`: Arduino (.ino) sketches.
- `/Schematics`: Wiring diagrams.
- `/Docs`: Original manuals and troubleshooting guides.

## 🔧 Installation & Usage
1. Clone this repo: `git clone [Your-Repo-Link]`
2. Install the required libraries (LiquidCrystal_I2C, Servo, BH1750).
3. Upload `Solar_Monitor.ino` to your Arduino UNO.
