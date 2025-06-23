# arduino-dht11-sensor
# Arduino DHT11 Temperature & Humidity Sensor

This Arduino project reads temperature and humidity data using the DHT11 sensor and prints the output to the serial monitor.

## Hardware Required

- Arduino board (UNO, Nano, etc.)
- DHT11 temperature & humidity sensor
- Jumper wires
- Breadboard (optional)

## Wiring

| DHT11 Pin | Arduino Pin |
|-----------|-------------|
| VCC       | 5V          |
| DATA      | D2          |
| GND       | GND         |

## Installation

1. Open Arduino IDE.
2. Install the "DHT sensor library" by Adafruit:
   - Go to **Sketch > Include Library > Manage Libraries...**
   - Search for "DHT sensor library"
   - Install the library by **Adafruit**
3. Also install "Adafruit Unified Sensor" library (required dependency).

## Usage

1. Connect your DHT11 sensor to the Arduino as per the wiring table.
2. Upload the code from `DHT11_Read.ino` to your Arduino board.
3. Open the Serial Monitor (baud rate: 9600) to view temperature and humidity readings every 2 seconds.
