# RPM Controller: C# Application and Arduino Integration

![App Screenshot](CsharpInterface.png)

## Description

This repository brings together a C# application and Arduino code to create an RPM Controller system. The C# application allows users to control the direction (Clockwise, CounterClockwise) and speed in RPM (0-300) for a motor. Additionally, users can specify the number of steps to be taken in each rotation. The application also prints the planned operations in a postgrid table, including distance and tool information.

The commands generated by the C# application are sent to an Arduino Mega 2560 board, which processes the instructions and displays the speed in RPM and direction on an attached LCD screen.

## Features

- **Direction control:** Choose between Clockwise and CounterClockwise rotation.
- **RPM adjustment:** Set the motor speed from 0 to 300 RPM.
- **Step configuration:** Specify the number of steps to take in each rotation.
- **Postgrid table:** Display the planned operations in a tabular format (distance and tool).
- **Arduino integration:** Send commands from the C# application to the Arduino board for processing.
- **LCD display:** View the motor speed and direction on an LCD screen attached to the Arduino board.

## Usage

1. Clone or download the repository.
2. Open the C# application in your preferred development environment (e.g., Visual Studio).
3. Connect the Arduino Mega 2560 board to your computer.
4. Upload the included Arduino code (`ArduinoCode.ino`) to the Arduino board.
5. Run the C# application to control the motor's direction, speed, and step configuration.
6. Monitor the LCD screen connected to the Arduino board for real-time speed and direction updates.

Feel free to explore and customize the C# application and Arduino code according to your specific requirements.

Please note that this project is provided as-is, and any usage or modification is at your own risk.

Enjoy controlling RPM with the C# application and Arduino integration!

## Enjoy :)
