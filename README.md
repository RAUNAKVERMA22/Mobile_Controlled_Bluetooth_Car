🚗 Mobile Controlled Bluetooth Car (Arduino + HC-05)
This project demonstrates how to build a Bluetooth-controlled robotic car using an Arduino UNO, a motor driver shield, and an HC-05 Bluetooth module.
The car can be controlled wirelessly using a smartphone app via Bluetooth connection.

📌 Features
Wireless control via HC-05 Bluetooth module
Supports movements: Forward, Backward, Left, Right, Stop
Beginner-friendly Arduino robotics project
Works with Android Bluetooth RC car apps
🛠️ Components Required
Arduino UNO board
Motor Shield (L293D / Adafruit AFMotor shield)
HC-05 Bluetooth module
DC Motors (x4) + Wheels
Robot chassis
Battery pack (2 × 18650 Li-ion cells or >4V, >1A battery for motors)
5V Power bank (to power Arduino)
Jumper wires and connectors
📲 Software Requirements
Arduino IDE
Arduino Bluetooth RC Car App (Android)
⚡ Circuit Connections
HC-05 Bluetooth Module

VCC → 5V
GND → GND
TX → RX (Arduino pin 0)
RX → TX (Arduino pin 1)
Motors via Motor Shield

Left motors → M3 & M4
Right motors → M1 & M2
(Swap wires if rotation is reversed)
Power

Arduino UNO → Powered via USB/power bank
Motors → External battery (≥ 7.4V recommended using 2 × 18650 cells in series)
🔧 Installation & Setup
Clone this repository or download ZIP.
Install AFMotor library:
Extract AFMotor folder to Documents/Arduino/libraries/.
Open the provided .ino file in Arduino IDE.
Select Board → Arduino UNO and correct Port.
Upload the program to Arduino.
📱 Usage
Power on the car (Arduino + motors).
Turn on Bluetooth on your phone.
Pair with HC-05 (default password: 1234).
Open the Arduino Bluetooth RC Car App.
Connect to HC-05 → Green light means connected.
Use arrows in the app to control movement.
⚠️ Troubleshooting
🔋 Motors running slow → Use a higher current battery (2 × 18650 Li-ion cells) instead of AA batteries.
🔄 Motors rotating in wrong direction → Swap motor wires on the motor shield.
⚡ Bluetooth not connecting → Ensure HC-05 baud rate = 38400 (default).
📚 References
Arduino Official Docs
HC-05 Bluetooth Module Guide
📜 License
This project is open-source and free to use for educational purposes.
