# Floor-cleaning-robot
This project is a prototype of an autonomous floor-cleaning robot designed to navigate 
and clean indoor spaces efficiently. The robot combines hardware components like 
Arduino UNO, sensors, and motor drivers with embedded software to detect obstacles, 
move autonomously, and perform cleaning tasks.

# Features
Autonomous navigation with obstacle detection and avoidance.
Cleaning mechanism (e.g., brushes or mopping system) for effective floor cleaning.
Modular design for easy upgrades or enhancements.
Energy-efficient operation for longer runtime.
Remote control and monitoring (future scope).
Hardware Components
# Arduino UNO: 
Microcontroller for controlling the robot.
# L293D Motor Driver Module: 
Controls DC motors for movement and cleaning.
# Ultrasonic Sensors:
Detects obstacles and guides navigation.
# DC Motors: 
Drives the wheels and cleaning mechanisms.
# Battery Pack: 
Powers the robot.

# Software Requirements
# Arduino IDE: 
For writing and uploading the robot’s control code.
C/C++:
Programming language used for the control logic.

# How It Works

Navigation: Ultrasonic sensors detect obstacles, and the Arduino UNO
processes the data to control motor movements.
Cleaning: Cleaning tools (e.g., brushes or mopping mechanisms) are 
powered by motors controlled via the L293D driver.
Power Management: Operates on battery power with efficient energy use
for extended runtime.

# Setup Instructions
Assemble Hardware: Mount components on the chassis and connect motors, sensors, and power supplies.
Upload Code:
Open the Arduino IDE.
Connect the Arduino UNO and upload the provided code.
Test the Robot: Power it on and observe its navigation and cleaning functions.
