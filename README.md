# Fire-Fighter-Robot-
IoT-based Fire Fighter Robot using Arduino, ESP8266 wifi, and ESP32-CAM. Features Bluetooth remote control, live Wi-Fi video streaming, and automatic flame detection with water pump suppression. Dual-controller architecture ensures  Wi-Fi operation, integrating embedded systems, IoT communication, and robotic automation.

This project presents a dual-controller IoT-based Fire Fighter Robot designed to detect and extinguish fire using both manual and automatic modes. The system integrates Arduino microcontrollers, ESP32-S (Bluetooth), and ESP32-CAM (Wi-Fi streaming) to enable remote navigation, live video monitoring, and automatic fire suppression.

The robot can be manually controlled via a Bluetooth-enabled mobile application, while the ESP32-CAM provides real-time video streaming for long-distance fire detection. Once the robot reaches the fire source, onboard flame sensors detect the flame and automatically activate a water pump to extinguish it.

This project demonstrates practical implementation of IoT systems, embedded programming, real-time communication, and robotic automation.

 Key Features

   1.Dual-controller architecture 

   2.Wifi-based remote control using ESP8266

   3.Live video streaming via ESP32-CAM (Wi-Fi)

   4.Short-range flame detection using multiple flame sensors

   5.Automatic water pump activation for fire suppression

   6. Buzzer and LED indicators for fire alerts

   7.Manual + Automatic operating modes

   8.Reliable separation of Wi-Fi and Bluetooth to avoid ESP32 limitations

 Technologies & Components Used

Arduino UNO / Nano

   1.ESP8266 (Wifi communication)

   2.ESP32-CAM (Live video streaming over Wi-Fi)

   3.L298N Motor Driver

   4.Flame Sensors (Left, Center, Right)

   5.Relay Module & Water Pump

   6.DC Motors & Chassis

   7.Embedded C/C++ (Arduino IDE)

   8.UART Serial Communication

   9.IoT-based connectivity concepts

 How It Works
  Manual Mode

   1.User connects mobile phone to ESP32-S via Bluetooth.

   2.Sends commands (F, B, L, R, S, P) to control movement and pump.

   3.ESP8266 drives motors through L298N motor driver.

  Automatic Mode

   1.ESP32-CAM streams live video for remote monitoring.

   2.Flame sensors connected to Arduino detect nearby fire.

   3.System automatically stops and activates the water pump.

   4.Buzzer and LED indicators provide visual/audio alerts.

Architecture

The system uses two microcontrollers to ensure smooth operation:

   ->ESP8266 → Handles Bluetooth and robot movement.

   ->Arduino + ESP32-CAM → Handles flame detection, alarms, and live streaming.

 This architecture prevents Wi-Fi and Bluetooth conflicts on a single ESP32 board and improves system reliability.

Project Outcome

  ->Successfully implemented real-time Bluetooth control.

 ->Achieved stable Wi-Fi video streaming.
 
 ->Automatic flame detection and fire suppression within 3–5 seconds.

 ->Demonstrated integration of IoT communication with robotics automation
