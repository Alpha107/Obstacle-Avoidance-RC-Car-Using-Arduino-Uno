# Obstacle Avoidance Robot Using Arduino Uno

An autonomous robot that detects and avoids obstacles using ultrasonic sensors. This project demonstrates sensor-based navigation and real-time decision-making.

---

## Introduction
The Obstacle Avoidance Robot is an autonomous vehicle designed to detect obstacles in its path and navigate around them without human intervention. Ultrasonic sensors measure the distance between the robot and nearby objects. The Arduino Uno processes the data and controls the motors to avoid collisions.

This project helps in understanding sensor interfacing, motor control, and real-time decision-making. Obstacle avoidance robots are widely used in autonomous vehicles, service robots, and indoor navigation systems.

---

## Components Used

| Component | Description | Purpose |
|-----------|------------|--------|
| 4-Wheel Chassis | Mechanical base with wheels | Robot structure |
| BO Motors (4) | DC geared motors | Vehicle movement |
| Arduino Uno | ATmega328P microcontroller | Main controller |
| Motor Driver | L298N Dual H-Bridge | Controls motor direction |
| Ultrasonic Sensor | HC-SR04 | Measures distance to obstacles |
| Servo Motor | Micro servo (SG90) | Sensor rotation for scanning |
| Buzzer | Piezo buzzer | Audio alert for obstacle detection |
| Jumper Wires | Connection cables | Circuit wiring |
| Batteries | Li-ion / AA | Power supply |
| Battery Holders | Secure battery placement | Power management |

---

## System Diagrams

### Block Diagram
![Block Diagram](images/block_diagram.png)  
*Ultrasonic sensors detect obstacles and send signals to the Arduino. Based on the data, the Arduino controls the motor driver to change direction or stop. Buzzer provides audio alerts.*

### Circuit Diagram
![Circuit Diagram](images/circuit_diagram.png)  
*Ultrasonic sensors, servo motors, and buzzer are connected to Arduino digital pins. Motor driver input pins receive signals from Arduino to drive the four DC motors. Batteries provide separate power for motors and controller.*

---

## Problems Faced
- Inaccurate distance measurements due to sensor noise  
- Limited detection angle of a single ultrasonic sensor  
- Power drain from running four motors simultaneously  
- Servo motor jitter during scanning  
- Heat generation in the L298N motor driver  
- Delays in obstacle detection at higher speeds  

---

## Future Improvements
- Use multiple ultrasonic or IR sensors for wider coverage  
- Implement smoother navigation algorithms  
- Replace L298N with a more efficient motor driver  
- Add PWM-based speed control  
- Integrate ESP32 for Wi-Fi or Bluetooth monitoring  
- Add mapping and path-planning capabilities  

---

## Conclusion
The Obstacle Avoidance Robot using Arduino Uno successfully demonstrates autonomous navigation through sensor-based obstacle detection. The project strengthened knowledge in ultrasonic sensors, servo control, and motor driver interfacing. Despite limitations in sensor accuracy and power efficiency, the robot reliably avoided obstacles, providing a solid foundation for advanced autonomous systems.

---

## Images
*(Replace the placeholders with your actual images)*  
![Obstacle Avoidance Front](images/obstacle_robot_front.png)  
![Obstacle Avoidance Top](images/obstacle_robot_top.png)
