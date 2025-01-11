README for ESP32 Web Server

Author: Alejandro Vivas

Description:

This project implements a simple web server on an ESP32 microcontroller. The server allows remote control of two GPIO pins (26 and 27) through a web interface.

Features:

*WiFi Connectivity: Connects to a specified Wi-Fi network.
*Web Server: Hosts a basic web page with on/off buttons for controlling the GPIO pins.
*GPIO Control: Controls the state of GPIO pins 26 and 27 based on web requests.
*User-friendly Interface: Provides a simple and intuitive web interface for interaction.


Hardware Requirements:

*ESP32 development board
*Wi-Fi network with known SSID and password
*Software Requirements:
*Arduino IDE with ESP32 support

Installation:

*Install the Arduino IDE: Download and install the Arduino IDE from the official website.
*Install ESP32 Board Support: Follow the instructions in the Arduino IDE to install the ESP32 board support packages.
*Upload the Code:
*Copy the provided code into the Arduino IDE.
*Replace ssid and password with your Wi-Fi network credentials.
*Upload the code to your ESP32 board.

Usage:

Connect to the ESP32's IP Address:

After uploading the code, the ESP32 will connect to your Wi-Fi network and print its IP address to the serial monitor.
Open a web browser and enter the IP address of the ESP32 in the address bar.
Control the GPIO Pins:

The web page will display the current state of GPIO pins 26 and 27.
Click the "ON" or "OFF" buttons to control the corresponding GPIO pin.
Note:

This is a basic example and can be further extended to include more features, such as controlling other devices, displaying sensor data, or implementing more complex logic.
The code includes basic error handling and timeout mechanisms.