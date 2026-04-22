# Fire-Fighting-Robot-with-Aurdino
An Arduino-powered Fire Fighter Robot capable of detecting flames using infrared sensors, navigating toward the fire source, and extinguishing it with a water pump. The system integrates real-time sensing, decision-making, and actuation, making it a practical demonstration of embedded systems and robotics for safety applications.

🔥 Fire Fighter Robot

Autonomous Fire Detection & Extinguishing System

An Arduino-based autonomous robot that detects and extinguishes fire using IR sensors, motor navigation, and a water pump system.

⸻

📌 Table of Contents

* Overview￼
* Features￼
* Hardware Components￼
* Circuit Design￼
* Working Principle￼
* Installation & Setup￼
* Usage￼
* Results￼
* Challenges￼
* Future Improvements￼
* Tech Stack￼
* Contributors￼
* License￼

⸻

📖 Overview

The Fire Fighter Robot is an embedded robotics project designed to:

* Detect fire using infrared flame sensors
* Navigate autonomously toward the fire source
* Extinguish fire using a water pump and servo-controlled nozzle

It demonstrates real-time decision-making and automation using Arduino UNO.

⸻

✨ Features

* 🔍 Multi-directional fire detection (Left, Front, Right)
* 🚗 Autonomous navigation using DC motors
* 💧 Automatic water spraying system
* 🔄 Servo-based nozzle sweeping for wide coverage
* ⚡ Fully automated — no human intervention required

⸻

🧰 Hardware Components

Component	Description
Arduino UNO	Microcontroller
IR Flame Sensors (x3)	Fire detection
L298N Motor Driver	Motor control
BO Motors + Wheels	Movement
Servo Motor	Nozzle control
Water Pump	Fire extinguishing
TIP122 Transistor	Pump switching
Li-ion Batteries	Power supply

⸻

🔌 Circuit Design

Motor Control

* Controlled via L298N motor driver
* PWM pins used for speed control

Flame Sensors

* Connected to analog pins:
    * Right → A0
    * Front → A1
    * Left → A2

Pump Circuit

* Controlled using TIP122 transistor
* Prevents overcurrent damage to Arduino

Servo Motor

* Controlled via PWM signal for angle-based spraying

⸻

⚙️ Working Principle

1. Sensors continuously detect fire intensity
2. Robot determines direction of fire
3. Moves toward fire source
4. Stops and activates pump
5. Servo sweeps nozzle to extinguish fire

⸻

🛠 Installation & Setup

1. Clone the repository:

git clone https://github.com/Anushkag01/Fire-Fighting-Robot-with-Aurdino.git

2. Open the Arduino code in Arduino IDE
3. Connect Arduino UNO via USB
4. Upload the code
5. Power the robot using batteries

⸻

▶️ Usage

* Turn ON the robot
* It will automatically:
    * Detect fire
    * Navigate toward it
    * Extinguish it

⸻

📊 Results

* Successfully detected fire in all directions
* Autonomous navigation worked reliably
* Water pump extinguished small flames effectively
* Servo improved spray coverage

⸻

⚠️ Challenges

* 🔌 Pump current issues → solved using transistor
* 📉 Sensor noise → calibrated thresholds
* 🔄 Servo instability → limited angle range
* ⚡ Electrical noise → added capacitor

⸻

🚀 Future Improvements

* Add thermal camera (Raspberry Pi integration)
* Implement Wi-Fi/Bluetooth control
* Add obstacle avoidance sensors
* Use CO₂ or foam extinguisher
* Integrate camera-based fire detection

⸻

💻 Tech Stack

* Arduino (C/C++)
* Embedded Systems
* Robotics
* Electronics

⸻

👥 Contributors

* Anushka Gupta , Arnav Lunia , Arya Suresh , Athreya 
* PES1UG23CS088,PES1UG23CS104,PES1UG23CS107
