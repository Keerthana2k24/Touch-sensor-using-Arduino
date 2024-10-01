## Touch Sensor LED Control Project
## Overview
This Arduino project controls three LEDs based on the input from a touch sensor. Each time the sensor is touched, the lighting mode changes, cycling through different LED behaviors.

## Components Required
1x Arduino Board (e.g., Arduino Uno)
1x Touch Sensor
3x LEDs
3x Resistors (220 ohms)
Jumper Wires
Breadboard

## Circuit Setup
Touch Sensor: Connect the touch sensor to digital pin 2 on the Arduino.
LED 1: Connect the positive leg (anode) of LED 1 to digital pin 9 through a 220-ohm resistor.
LED 2: Connect the positive leg (anode) of LED 2 to digital pin 10 through a 220-ohm resistor.
LED 3: Connect the positive leg (anode) of LED 3 to digital pin 11 through a 220-ohm resistor.
Connect all the negative legs (cathode) of the LEDs to the ground (GND) on the Arduino.
## Steps to Set Up Arduino IDE and Run the Code
1. Install Arduino IDE
Go to the official Arduino website: https://www.arduino.cc/en/software
Download the Arduino IDE for your operating system (Windows, macOS, Linux).
Follow the installation instructions for your OS to install the Arduino IDE.
2. Connect the Arduino Board
Plug your Arduino board into your computer using a USB cable.
Wait for the operating system to recognize the board.
3. Open Arduino IDE
Launch the Arduino IDE that you just installed.
4. Select Your Arduino Board
In the Arduino IDE, go to the menu: Tools > Board > [Your Board Name].
For most projects, select Arduino Uno.
7. Verify the Code
Click the Checkmark (✔) button in the top-left corner of the Arduino IDE to verify the code.
This step will check for syntax errors.
8. Upload the Code
Once the code is verified without errors, click the Arrow (→) button to upload the code to the Arduino board.
9. Run the Project
After uploading, your Arduino board will start executing the code, and you can interact with the touch sensor to see the LED behaviors.
## How It Works
Touch Sensor Input: Each time the touch sensor is pressed, it increments the mode variable.
LED Behavior:
Mode 0: All LEDs off.
Mode 1: Only LED 1 on.
Mode 2: Only LED 2 on.
Mode 3: Only LED 3 on.
Mode 4: All LEDs blink on and off.
Mode 5: All LEDs off, and the mode variable resets to 0.
## License
This project is open-source and free to use under the MIT License.

