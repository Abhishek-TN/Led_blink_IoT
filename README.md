# LED Blink Code for ESP32 using Arduino IDE

## Overview
This code demonstrates how to blink an LED connected to an ESP32 microcontroller using the Arduino IDE. The LED blinks on and off with a delay of 2 seconds between each state change.

## Hardware Requirements
- ESP32 development board
- LED
- Resistor (if required for the LED)
- Jumper wires

## Setup Instructions
1. Connect the LED to the ESP32 board. If you're using the built-in LED (pin 42 on some ESP32 boards), you can skip this step.
2. If not using the built-in LED, connect the longer leg (anode) of the LED to a digital pin on the ESP32 (e.g., GPIO pin).
3. Connect the shorter leg (cathode) of the LED to the ground (GND) pin on the ESP32.
4. If necessary, add a current-limiting resistor in series with the LED to prevent it from burning out.

## Installing Arduino IDE
1. Download and install the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/software).
2. Open the Arduino IDE.

## Setting Up ESP32 in Arduino IDE
1. Open Arduino IDE.
2. Go to File > Preferences.
3. Enter `https://dl.espressif.com/dl/package_esp32_index.json` into the "Additional Board Manager URLs" field.
4. Click OK to close the Preferences window.
5. Go to Tools > Board > Boards Manager.
6. Search for "esp32" and install "esp32 by Espressif Systems".
7. After installation, select your ESP32 board from Tools > Board.

## Uploading the Code
1. Copy the provided code into a new sketch in Arduino IDE.
2. Connect your ESP32 board to your computer via USB.
3. Select the appropriate COM port from Tools > Port.
4. Click the "Upload" button to compile and upload the code to your ESP32 board.

## Running the Code
1. Once the code is uploaded successfully, the LED connected to your ESP32 should start blinking on and off with a delay of 2 seconds between each state change.
2. If you're using a different pin than the built-in LED, make sure to adjust the `led` variable in the code to match your pin assignment.

## Troubleshooting
- If the LED doesn't blink as expected, double-check your connections and ensure the correct pin is configured in the code.
- If you encounter any errors during compilation or upload, refer to the error messages in the Arduino IDE for troubleshooting guidance.
