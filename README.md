# Line-follower-robot-

# Overview
This project is a line follower robot built using the Raspberry Pi Pico microcontroller board, an L298N motor driver, and IR sensors. The robot is designed to autonomously detect and follow a path, maintaining a steady movement along a line using real-time sensor feedback.

# Components Used
Microcontroller: Raspberry Pi Pico
Motor Driver: L298N
IR Sensors: For line detection
Motors: DC motors for movement
Power Supply: Battery pack for portable operation
Chassis: Robot body frame
# Features
Real-Time Line Detection: Utilizes IR sensors to detect and follow the line accurately.
Smooth Motor Control: Controlled using the L298N motor driver to ensure stable and reliable movements.
Efficient Microcontroller Processing: The Raspberry Pi Pico is used for processing sensor inputs and sending commands to the motor driver.
# How It Works
IR Sensors: The sensors detect the reflectivity of the surface. The black line absorbs IR light, while a white surface reflects it, allowing the robot to follow the line.
Microcontroller Logic: The Raspberry Pi Pico reads the input from the IR sensors and adjusts the motor speed and direction accordingly.
Motor Control: The L298N motor driver acts as an interface between the Raspberry Pi Pico and the DC motors, managing the power flow and motor movement.
# Circuit Diagram

IR sensors connected to the GPIO pins of the Raspberry Pi Pico.
L298N motor driver connected to the output pins for motor control.
Power source connected to the motor driver and Raspberry Pi Pico.
# Code Explanation
The code reads sensor data and adjusts the motor speed to ensure the robot follows the line. Logic includes conditions to determine if the robot should move straight, turn left, or turn right based on sensor input.

# Installation and Usage
Connect the components as per the circuit diagram.
Upload the provided code to the Raspberry Pi Pico using an IDE like Thonny.
Place the robot on a surface with a track to follow and power it up.
# Future Enhancements
Add obstacle detection using ultrasonic sensors.
Implement PID control for smoother turns and enhanced accuracy.
Demo Video and Photos
Include links or images showcasing the project in action.

# License
This project is licensed under the MIT License. Feel free to use and modify it.
