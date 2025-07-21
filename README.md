# Bluethooth-jammer

This project demonstrates a low-cost educational Bluetooth jamming system built using an ESP32 microcontroller and NRF24L01 wireless module. It showcases the vulnerability of Bluetooth communication within the 2.4 GHz ISM band, commonly used by many wireless technologies.

Features:
Sends constant interference signals to disrupt Bluetooth communication.
Uses NRF24L01 to flood the 2.4 GHz spectrum.
Controlled via ESP32 (Arduino IDE or PlatformIO).
Educational purpose only – demonstrates wireless jamming techniques.

Objectives:
Raise awareness of Bluetooth communication vulnerabilities.
Understand jamming concepts and RF interference.
Provide a hands-on cybersecurity demonstration.

Components uses:
ESP32,
NRF24L01+ Module,
Capacitor (10µF),
Breadboard,,
Jumper Wires
Micro USB Cable,
Power Supply (5V).

Working Description:
The ESP32 controls the NRF24L01 module to continuously transmit noise signals over the 2.4 GHz ISM band, the same frequency range used by Bluetooth devices. This interference disrupts Bluetooth communication by flooding the channel with unwanted packets, effectively jamming nearby Bluetooth connections.








