# Electrical System

## Overview
The electrical subsystem controlled vehicle movement and launcher activation. The design focused on reliability, simplicity, and repeatable competition performance.

## Main Components

### Arduino Uno
The Arduino Uno acted as the central controller responsible for timing vehicle movement and activating the launcher sequence.

### Motor Controller
An L298N motor controller was used to regulate power delivery between the battery pack and the DC motor.

### DC Motor
A single DC motor powered the drivetrain through the pulley system.

### Power System
The vehicle used AA batteries and a battery holder assembly to provide portable power during competition operation.

### Breadboard and Wiring
A breadboard and jumper wiring network were used to connect the Arduino, motor controller, passive components, and launcher electronics.

## Electrical Design Philosophy
Instead of using sensors, the vehicle used deterministic timing logic. Because the competition environment was fixed and repeatable, timing-based control reduced complexity while maintaining reliability.

## Reliability Considerations
- Secure wire routing
- Protected electronics placement
- Accessible maintenance through hinged roof design
- Simplified wiring architecture

## Future Improvements
- Rechargeable battery system
- Printed circuit board integration
- Sensor-based navigation
- Wireless diagnostics
- Motor encoder feedback
