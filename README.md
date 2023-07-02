# RFID Card Reader with NodeMCU ESP8266

This project demonstrates how to use a NodeMCU ESP8266 board along with an MFRC522 RFID card reader to read RFID tags and send the UID to a server using HTTP requests. It connects to a Wi-Fi network and sends the UID data to specified URLs.

## Prerequisites

- Arduino IDE (https://www.arduino.cc/en/software)
- NodeMCU ESP8266 board package
- MFRC522 library by Miguel Balboa
- ESP8266WebServer library
- ESP8266HTTPClient library

## Hardware Components

- NodeMCU ESP8266 board
- MFRC522 RFID card reader
- RFID tags or keychains

## Circuit Diagram

Insert a circuit diagram here if applicable.

## Installation

1. Install the Arduino IDE from the official Arduino website.
2. Install the NodeMCU board package in the Arduino IDE.
3. Install the MFRC522 library and the required ESP8266 libraries using the Arduino Library Manager.
4. Connect the MFRC522 RFID card reader to the NodeMCU ESP8266 board according to the circuit diagram.
5. Connect the NodeMCU board to your computer via USB.
6. Open the Arduino IDE, create a new sketch, and copy the code provided in the `sketch.ino` file.
7. Customize the Wi-Fi credentials and the server URLs in the code to match your setup.
8. Compile and upload the sketch to the NodeMCU board.
9. Open the Serial Monitor to view the output and check for successful connection and RFID tag readings.

## Usage

1. Power on the NodeMCU board.
2. The board will attempt to connect to the specified Wi-Fi network. The onboard LED will indicate the connection status.
3. Once connected, the board will start reading RFID tags.
4. When a tag is detected, the UID will be sent to the specified server URLs using HTTP POST requests.
5. The response from the server will be displayed in the Serial Monitor.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

