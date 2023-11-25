ESP32 Bluetooth Relay Control

This project demonstrates a simple home automation setup using an ESP32 microcontroller and Bluetooth communication. The ESP32 is equipped with a 4-channel relay module, allowing control of up to four electrical devices. An Android app, created using MIT App Inventor, serves as the interface for relay control via Bluetooth.

Features:

Bluetooth Communication: Establishes a Bluetooth serial connection between the ESP32 and an Android device for wireless control.
Relay Control: Toggles four relays (corresponding to four electrical devices) on and off based on commands received via Bluetooth.
MIT App Inventor Android App: A custom Android app provides a user-friendly interface with buttons to control each relay.
Getting Started:

Hardware Setup: Connect the ESP32 to the 4-channel relay module as per the provided wiring guide.
Arduino Code: Upload the provided Arduino code to the ESP32 using the Arduino IDE.
Android App Setup:
Create an Android app using MIT App Inventor.
Add Bluetooth client functionality to send commands to the ESP32 based on button clicks.
Pair Devices: Ensure that your Android device is paired with the ESP32's Bluetooth.
Run the System: Launch the Android app and start controlling the relays wirelessly.
Code Structure:

esp32_bluetooth_relay_control.ino: Arduino code for the ESP32, managing Bluetooth communication and relay control.
Dependencies:

BluetoothSerial Library
License:

This project is licensed under the MIT License.

Feel free to explore, modify, and enhance the code for your specific needs. Happy tinkering!
