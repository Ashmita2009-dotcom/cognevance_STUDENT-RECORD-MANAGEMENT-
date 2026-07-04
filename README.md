# cognevance_STUDENT-RECORD-MANAGEMENT-

PROJECT 
Smart Obstacle Avoiding Robot

Author

Ashmita R

Project Overview

The Smart Obstacle Avoiding Robot is an Arduino-based autonomous robot that detects obstacles using an HC-SR04 ultrasonic sensor and avoids collisions by changing its direction. The project demonstrates the fundamentals of robotics, embedded systems, sensor integration, and motor control.

Objectives

* Study basic robotics concepts.
* Interface an ultrasonic sensor with Arduino.
* Control DC motors using the L298N motor driver.
* Implement obstacle detection and avoidance logic.
* Test autonomous robot movement.

Hardware Used

* Arduino UNO
* HC-SR04 Ultrasonic Sensor
* L298N Motor Driver
* 2 × DC Motors
* Robot Chassis
* Wheels
* Battery Pack
* Jumper Wires

Software Used

* Arduino IDE
* Tinkercad (optional)
* GitHub

Workflow

1. Power on the robot.
2. Ultrasonic sensor continuously measures distance.
3. If no obstacle is detected, the robot moves forward.
4. If an obstacle is detected within 20 cm:
    * Stop
    * Turn left
    * Continue moving forward

Applications

* Autonomous mobile robots
* Educational robotics
* Warehouse automation
* Obstacle avoidance systems

Future Improvements

* Bluetooth control
* Wi-Fi monitoring
* AI-based object detection
* Voice control

cognevance_SmartObstacleAvoidingRobot

├── README.md
├── Source_Code
│   └── SmartObstacleAvoidingRobot.ino
├── Circuit_Diagram
│   └── Circuit_Diagram.png
├── Documentation
│   └── Project_Report.pdf
├── Screenshots
├── Testing
└── Simulation

Project Report

Title

Smart Obstacle Avoiding Robot Using Arduino

Abstract

This project presents the design and implementation of a smart obstacle avoiding robot using Arduino UNO. The robot utilizes an ultrasonic sensor to detect nearby obstacles and automatically changes direction to avoid collisions. It demonstrates the integration of sensors, motor control, and embedded programming in an autonomous robotic system.

Objectives

* Learn Arduino programming.
* Interface ultrasonic sensors.
* Control DC motors.
* Build an autonomous navigation system.

Components Used

* Arduino UNO
* HC-SR04 Sensor
* L298N Motor Driver
* DC Motors
* Battery
* Chassis
* Wheels

Working Principle

The ultrasonic sensor measures the distance to nearby objects. The Arduino continuously processes the sensor data. When the measured distance falls below the predefined threshold, the robot stops, turns, and resumes forward movement.

Advantages

* Low cost
* Easy to build
* Autonomous operation
* Beginner-friendly

Applications

* Service robots
* Educational projects
* Smart navigation systems

Conclusion

The project successfully demonstrates autonomous obstacle detection and avoidance using Arduino. It provides practical experience in robotics, embedded systems, and sensor integration.