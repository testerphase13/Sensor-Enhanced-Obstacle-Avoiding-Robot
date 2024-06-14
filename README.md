# Sensor-Enhanced Obstacle-Avoiding Robot

## Overview

The Sensor-Enhanced Obstacle-Avoiding Robot is a project designed to navigate autonomously while avoiding obstacles using various sensors. This project integrates ultrasonic sensors to detect obstacles and adjusts the robot's path to prevent collisions.

## Features

- **Obstacle Detection:** Utilizes ultrasonic sensors to detect obstacles in the path.
- **Autonomous Navigation:** The robot adjusts its path autonomously based on sensor input.
- **Efficient Algorithm:** Implements an efficient algorithm to ensure smooth and quick navigation.

## Components

- **Microcontroller:** Arduino Uno
- **Sensors:** HC-SR04 & LIDAR
- **Motors:** DC motors with motor driver (L298N)
- **Power Supply:** 9V battery
- **Chassis:** 4-wheel robot chassis
- **Software:** Arduino IDE for programming

## Setup and Installation

1. **Assemble the Robot:**
   - Attach the motors to the chassis.
   - Connect the motor driver to the motors and the microcontroller.
   - Mount the ultrasonic sensors at the front of the robot.

2. **Wiring:**
   - Connect the ultrasonic sensors to the Arduino pins.
   - Connect the motor driver inputs to the Arduino.
   - Ensure all connections are secure and properly insulated.

3. **Programming:**
   - Install the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/software).
   - Upload the provided code to the Arduino.

4. **Power Up:**
   - Connect the battery to power up the robot.
   - Ensure all components are functioning correctly.

## Usage

- Place the robot on a flat surface with obstacles.
- Turn on the power supply.
- The robot will start moving forward and avoid obstacles autonomously.
