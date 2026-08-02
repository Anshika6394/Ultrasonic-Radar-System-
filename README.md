 # Ultrasonic Radar System using Arduino

## Project Overview

The Ultrasonic Radar System is an Arduino-based project that detects nearby objects using an HC-SR04 ultrasonic sensor mounted on a servo motor. The servo rotates from 15° to 165°, allowing the sensor to scan the surrounding area. The distance and angle data are sent to a Processing application, which displays a real-time radar visualization similar to an actual radar screen.

---

## Features

- Real-time object detection
- 180° radar scanning using servo motor
- Live radar visualization using Processing IDE
- Distance measurement using HC-SR04 Ultrasonic Sensor
- Serial communication between Arduino and Processing
- Easy to build and beginner-friendly

---

## Components Required

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Breadboard
- Jumper Wires
- USB Cable
- Computer with Arduino IDE & Processing IDE

---

## Software Used

- Arduino IDE
- Processing IDE
- Java (Processing)
- Git & GitHub

---

## Folder Structure

```
Ultrasonic-Radar-System/
├── Arduino_Code/
├── Processing_Code/
├── Images/
├── Demo/
├── README.md
└── LICENSE
```

---

## Working Principle

1. The servo motor rotates the ultrasonic sensor.
2. The HC-SR04 measures the distance of nearby objects.
3. Arduino sends angle and distance values through Serial Communication.
4. Processing receives the data.
5. A radar interface is displayed in real time.

---

## Future Improvements

- Wireless monitoring
- AI-based object classification
- Mobile App Integration
- 360° Scanning
- Data Logging

---

## Author

**Anshika Kushwaha**

B.Tech Electronics & Communication Engineering

---

## License

This project is licensed under the MIT License.
