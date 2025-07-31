# 🏠 Smart Home Automation System using Arduino

This project implements a Smart Home Automation System using Arduino, integrating various sensors and actuators to enhance household **convenience, safety, and energy efficiency**. It automates lighting based on occupancy, protects clothes from rain, and alerts residents in case of fire or gas leakage.

## ⚙️ Features

- **Occupancy-Based Lighting**  
  Automatically turns ON/OFF lights based on people entering and exiting the room using ultrasonic sensors.

- **Rain Detection with Clothesline Control**  
  Retracts the terrace clothesline using a servo motor when rain is detected.

- **Flame and Fire Detection**  
  Detects fire and triggers a fast-beeping buzzer alarm, along with a visual alert on the LCD.

- **Gas Leak Detection**  
  Monitors air quality using an MQ-135 sensor and sounds an alert if gas levels exceed a calibrated threshold.

- **User Interface with LCD**  
  Displays welcome/goodbye messages, live people count, system status, and hazard alerts.

- **Buzzer Alerts**  
  Different tones and patterns for rain, gas, and fire alerts.

## 🧠 Skills Demonstrated

- Embedded Systems (Arduino)
- Sensor Integration
- Hardware Logic Design

## 🧰 Components Used

| Component            | Function                                  |
|----------------------|-------------------------------------------|
| Arduino UNO / Nano   | Main microcontroller                      |
| Ultrasonic Sensors   | People entry/exit detection               |
| Rain Sensor          | Detects rainfall                          |
| Flame Sensor         | Fire detection                            |
| MQ-2 Gas Sensor      | Gas leakage detection                     |
| Servo Motor          | Controls clothesline movement             |
| Relay Module         | Controls room light                       |
| Buzzer               | Alerts for fire, gas, and rain            |
| LCD Display (I2C)    | Visual output and status messages         |

## 🚀 Future Improvements

- Add ESP32-based IoT support for cloud connectivity and remote monitoring.
- Integrate fan/AC control based on temperature and humidity.
- Include app/dashboard for manual override and alerts.
- Support voice assistant control (e.g., Alexa/Google Home).
