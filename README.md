# Home Automation System with ESP8266 and Blynk

This project is a home automation system designed to control relays, read sensors, and integrate with cloud-based services using an ESP8266 module. It allows users to control home appliances, monitor temperature and humidity, and receive real-time status updates.

## Features:
- **Relay Control**: Allows users to control up to 4 relays (for appliances) through Blynk or physical switches.
- **Sensor Monitoring**: Monitors temperature and humidity using a DHT11 sensor and sends updates to Blynk.
- **IR Remote Control**: Controls the relays via an IR remote.
- **Wi-Fi and Cloud Integration**: Connects to Wi-Fi and integrates with Blynk for remote control and monitoring.
- **Switch Debouncing**: Handles flip-switch debouncing to prevent false triggers.
  
## Hardware:
- **ESP8266 Module**: The main controller.
- **DHT11 Sensor**: For temperature and humidity readings.
- **IR Receiver**: For receiving signals from an IR remote.
- **Relays**: To control home appliances.
- **Physical Switches**: For manual control of relays.
  
## Software:
- **Blynk App**: For controlling relays and viewing sensor data remotely.
- **SinricPro**: For integration with smart home services.

### Required Libraries:
- **ESP8266WiFi**: For Wi-Fi connectivity.
- **SinricPro**: For smart home integration.
- **BlynkSimpleEsp8266**: For Blynk app communication.
- **DHT**: For reading temperature and humidity data.
- **IRremote**: For IR remote control functionality.

## Installation:
1. Clone this repository to your local machine.
2. Open the code in Arduino IDE.
3. Replace the `ssid`, `pass`, `Blynk` credentials, and device IDs with your own.
4. Upload the code to your ESP8266.

## How it Works:
1. **Wi-Fi Setup**: The system connects to the specified Wi-Fi network.
2. **Relay Control**: Users can control relays using the Blynk app or physical switches. Each relay can be toggled remotely.
3. **Sensor Monitoring**: Temperature and humidity data are read from the DHT11 sensor and displayed in the Blynk app.
4. **IR Control**: The system can also be controlled using an IR remote, with predefined button codes.
5. **Physical Switches**: The physical switches provide manual control of the relays.

## Video Demo:
For a demonstration of the system in action, please check out the video:  
[Home Automation Demo Video](Output-Video.mp4)

## License:
This project is open-source and released under the MIT License.

Feel free to use, modify, and contribute to this project.

