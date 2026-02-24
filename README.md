# Fire-Fighter-Robot-
IoT-based Fire Fighter Robot using Arduino, ESP32-S, and ESP32-CAM. Features Bluetooth remote control, live Wi-Fi video streaming, and automatic flame detection with water pump suppression. Dual-controller architecture ensures smooth Bluetooth and Wi-Fi operation, integrating embedded systems, IoT communication, and robotic automation.

This project presents a dual-controller IoT-based Fire Fighter Robot designed to detect and extinguish fire using both manual and automatic modes. The system integrates Arduino microcontrollers, ESP32-S (Bluetooth), and ESP32-CAM (Wi-Fi streaming) to enable remote navigation, live video monitoring, and automatic fire suppression.

The robot can be manually controlled via a Bluetooth-enabled mobile application, while the ESP32-CAM provides real-time video streaming for long-distance fire detection. Once the robot reaches the fire source, onboard flame sensors detect the flame and automatically activate a water pump to extinguish it.

This project demonstrates practical implementation of IoT systems, embedded programming, real-time communication, and robotic automation.

 Key Features

   1.Dual-controller architecture (Arduino 1 & Arduino 2)

   2.Bluetooth-based remote control using ESP32-S

   3.Live video streaming via ESP32-CAM (Wi-Fi)

   4.Short-range flame detection using multiple flame sensors

   5.Automatic water pump activation for fire suppression

   6. Buzzer and LED indicators for fire alerts

   7.Manual + Automatic operating modes

   8.Reliable separation of Wi-Fi and Bluetooth to avoid ESP32 limitations

 Technologies & Components Used

Arduino UNO / Nano

ESP32-S (Bluetooth communication)

ESP32-CAM (Live video streaming over Wi-Fi)

L298N Motor Driver

Flame Sensors (Left, Center, Right)

Relay Module & Water Pump

DC Motors & Chassis

Embedded C/C++ (Arduino IDE)

UART Serial Communication

IoT-based connectivity concepts

 How It Works
Manual Mode

User connects mobile phone to ESP32-S via Bluetooth.

Sends commands (F, B, L, R, S, P) to control movement and pump.

Arduino 1 drives motors through L298N motor driver.

Automatic Mode

ESP32-CAM streams live video for remote monitoring.

Flame sensors connected to Arduino 2 detect nearby fire.

System automatically stops and activates the water pump.

Buzzer and LED indicators provide visual/audio alerts.

Architecture

The system uses two microcontrollers to ensure smooth operation:

Arduino 1 + ESP32-S → Handles Bluetooth and robot movement.

Arduino 2 + ESP32-CAM → Handles flame detection, alarms, and live streaming.

This architecture prevents Wi-Fi and Bluetooth conflicts on a single ESP32 board and improves system reliability.

 Project Outcome

Successfully implemented real-time Bluetooth control.

Achieved stable Wi-Fi video streaming.

Automatic flame detection and fire suppression within 3–5 seconds.

Demonstrated integration of IoT communication with robotics automation
