# Hexapod_Summer_Project_2025

## Overview
This repository contains the code and documentation for the Hexapod Summer Project 2025. The goal of this project is to build and program a hexapod robot with various gait control algorithms, inverse kinematics, and forward kinematics solutions. The robot will be powered by a Teensy microcontroller.

## Project Structure

- **3_GAITS.ino**: Arduino code that contains three distinct gaits for the hexapod.
- **Forward_kinematics.py**: Python script for solving the forward kinematics of the hexapod's leg movement.
- **Teensy_code.ino**: Teensy-based microcontroller code for controlling the hexapod's motion.
- **hexapod_ik_solution.py**: Python script that calculates the inverse kinematics solution for the hexapod.
- **README.md**: This file, providing an overview of the project.

## Requirements
To run this project, the following software and hardware are required:
- **Hardware**:
  - Teensy microcontroller
  - Hexapod frame with servos
  - Power supply for the robot
- **Software**:
  - Arduino IDE for uploading code to the Teensy
  - Python 3.x for running the kinematics scripts
  - Required Python libraries (e.g., numpy)

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/RoboticsClubIITK/Hexapod_Summer_Project_2025.git
cd Hexapod_Summer_Project_2025
