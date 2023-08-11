# An Obstacle Avoiding Robot in Arduino

Welcome to this repository containing the source code for an Obstacle Avoidance Robot built with Arduino (A C++ Framework).

Note: Due to the presence of hardware components, the complete Arduino UNO [kit](https://store.arduino.cc/products/arduino-starter-kit-multi-language) is necessary to see the robot in operation.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributions](#contributions)
- [License](#license)

## Introduction

This robot is designed to navigate its environment while identifying obstacles in its path. It utilizes an ultrasonic sensor to detect obstacles and then employs the following code to determine the optimal path to avoid colliding with those obstacles.

## Dependencies

To run this implementation, you need:

- Arduino IDE
- The `AFMotor` library (follow the steps [here](https://learn.adafruit.com/adafruit-motor-shield/library-install) to install the library)
- The `NewPing` library (follow the steps [here](https://github.com/livetronic/Arduino-NewPing) to install the library)
- The `Servo` library (follow the steps [here](https://github.com/arduino-libraries/Servo.git) to install the library)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/elcruzo/obstacle-avoidance-robot.git
   cd obstacle-avoidance-robot
   ```

2. Ensure you have the Arduino IDE installed. You can check by searching:
   
   'Arduino IDE' in the apps list on your machine.

   If Python is not installed, you can download it from the official [Arduino website](https://www.arduino.cc/en/software/).

## Usage

1. Navigate to the project directory containing the `index.ino` file.

2. Open the `index.ino` file in the Arduino IDE.

3. Include the downloaded libraries in your Arduino IDE by:
   
   Go to sketch >> Include Library >> Add .ZIP File >> Select the Downloaded libraries (ZIP files)

4. Upload the `index.ino` sketch to the Arduino UNO using a data-transfer USB-B cord (included in the complete Arduino kit)

5. Upon uploading, you can proceed to see the assembled robot (with the Arduino UNO) in action.
## Example

Here's a brief example of how to run the code:

```bash
git clone https://github.com/elcruzo/gui-calc.git
cd gui-calc
python3 index.py
```

You will see a change show up on the text grid with each click of a button, displaying the result when you perform operations.

 

## Contributions

Contributions to this repository are welcome! If you have any improvements or feature suggestions, feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Have fun exploring my GUI Calculator! If you have any questions or run into issues, don't hesitate to ask for help.
