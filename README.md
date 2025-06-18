# Home-Connect
Design Thinking and Innovation Project

🏠 Home Connect – Affordable Smart Home Automation
Home Connect is a smart home system designed to modernize traditional households by retrofitting existing appliances with cost-effective and user-friendly IoT-based controls. Built with ESP32/ESP8266 microcontrollers, the system offers centralized automation and monitoring through a web-based interface, empowering users to manage lighting, temperature, humidity, irrigation, laundry, and security—all in real time.

🚀 Features
🌡️ Real-Time Monitoring: Track temperature, humidity, light intensity, gas leaks, and soil moisture.

🔁 Manual & Automatic Control: Dual-mode operation with configurable thresholds for automation.

🧠 Parent-Child Microcontroller Architecture: Distributed control using ESP32 and ESP8266 modules.

💧 Automated Irrigation: Soil moisture sensors activate motors for plant watering.

🔒 Security Monitoring: Light sensors detect intrusions; buzzer and alerts for gas leaks.

🧺 Laundry Notifications: Vibration sensors track washing machine activity.

🔌 Web Interface: Simple and secure control via Wi-Fi-accessible dashboard.

⏱️ Timers: Track active durations of devices to monitor usage.

🧩 System Architecture
Parent Node (ESP32): Central controller for sensors and actuators.

Child Nodes (ESP8266): Handle auxiliary tasks (e.g., laundry, security) and report to the parent.

Sensors Used:

DHT11 (temperature & humidity)

MQ-9 (gas leak detection)

Soil Moisture Sensor

LDR (light intensity)

Vibration Sensor

Actuators Used:

4-channel relay (lights, fan, motor)

Submersible pump

Buzzer

LEDs

🧰 Tech Stack
Hardware: ESP32, ESP8266, relays, sensors, 9V battery, transistors, diodes

Software:

Arduino IDE for microcontroller programming

VS Code for front-end development

HTML/CSS/JavaScript for website interface

C/C++ for embedded logic

🖥️ Website Interface
Hosted via ESP32 with unique IP for each node

Threshold configuration and real-time sensor display

Manual override options for all appliances

🧪 Setup & Deployment
Flash ESP32/ESP8266 with Arduino IDE using provided .ino files

Connect devices and sensors as per the circuit diagram

Access the dashboard via the ESP32’s IP address

Configure thresholds and enjoy real-time automation!

⚙️ Implementation Strategy
Modular upgrade kits reduce cost

Plug-and-play components simplify installation

Unified control via centralized website

Voice control and multilingual interface (future scope)

🧠 Key Innovations
JSON-based real-time data sync

Parent-child fallback hierarchy for resilience

Compact, intuitive dashboard layout

Energy-saving and safety-enhancing features

📊 Challenges Overcome
Voltage compatibility for diverse components

Real-time website synchronization

Sensor damage and replacements

PCB integration for ease of connections

Safe power supply alternatives (Hi-Link replacement)

👥 Contributors
IIIT Allahabad:

Rohitashwa Mishra

Jaseel Muhammad

Harini Balaga

Vaishnavi Gunda

Abhinav Chaudhary

Esha Vangapandu

Arpit Kumar

Kavin Prakash

Mukesh Choudhary

Abhiram Nemani

📄 License
This project is for academic use and research purposes. Feel free to fork, explore, and contribute with credits to the team.

