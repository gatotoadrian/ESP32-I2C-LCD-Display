# ESP32 I2C LCD Display

This project demonstrates how to use an ESP32 with an I2C LCD display to show text messages. The LCD is initialized, and a welcome message is printed on the screen.

## Requirements

- ESP32 board (NodeMCU-32S or similar)
- I2C LCD Display (16x2 or 20x4)
- Arduino IDE with ESP32 board support

## Libraries

Make sure to install the necessary libraries via the Arduino Library Manager:
- `hd44780`

## Hardware Setup

1. **I2C LCD Connections:**
   - VCC to 3.3V or 5V (depending on your LCD module)
   - GND to GND
   - SDA to GPIO 21
   - SCL to GPIO 22


