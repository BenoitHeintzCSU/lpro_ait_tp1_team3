<!--# Correction
* <span style="color:red">Put **/procedures** and **/pictures** folders in **/docs**.</span>
* <span style="color:red">Exact same remarks as the other procedure.... please read them!</span>-->

# LPro AIT 2019 - TP1 - Assembly procedure : motor to the arduino

- Names
    - Loris ARNAUD
    - Augustin GARES

The 7th of March of 2019

## Purpose of the document

- This document is a procedure that have to be used to assemble the motor and its support to an arduino UNO to control the motor.

## 1. Hardware list

- EMG30 motor with blue support assembly X1

    <img src="../Pictures/assembly5.jpg" width="400px"/>

- Arduino Uno X1

    <img src="../Pictures/arduino.jpg" width="400px"/>

- Arduino shield - Pololu DRV8835 Dual Motor Driver with jumper X1

    <img src="../Pictures/shield-motor.jpg" width="400px"/>

- Laptop X1

    <img src="../Pictures/laptop.jpg" width="400px"/>
    
- USB câble X1

    <img src="../Pictures/USB-cable.jpg" width="400px"/>

## 2. Tools

- Flathead screwdriver X1

    <img src="../Pictures/screwdriver.jpg" width="400px"/>

## 3. Assembly procedure : motor to the arduino

### 1. Download the program
- Download the arduino program motor_control_open_loop on the laptop. This program is in the folder */sources/motor_control_open_loop*.

<img src="../Pictures/laptop.jpg" width="400px"/>

### 2. Download the librarie
- Download the DRV8835MotorShield librarie into the arduino IDE. [How to install the library](https://github.com/pololu/drv8835-motor-shield).

### 3. Laptop-arduino wiring
- Wire the laptop to the arduino with the USB cable.

<img src="../Pictures/USB-Arduino.jpg" width="400px"/>

<img src="../Pictures/USB-PC.jpg" width="400px"/>

### 4. LED blinking
- Download the *motor_control_open_loop* software on the arduino UNO and verify if the LED blinks every 2 secondes on the arduino. After, unwire the USB cable from the arduino and the laptop.

### 5. Jumper wiring
- Put the jumper on the motor shield on the VOUT pin, like on the picture.

<img src="../Pictures/shield-motor-with-jumper.jpg" width="400px"/>

### 6. Pin the shield
- Pin the arduino shield on the arduino. The Vcc pin of the shield have to be on the 5V pin of the arduino. Verify that pins of the shield are on rights pins of the arduino.

<img src="../Pictures/assembly6.jpg" width="400px"/>

<img src="../Pictures/assembly7.jpg" width="400px"/>

### 7. Plug the motor wires to the motor shield
- Plug the red and black wires of motor in the M1B and M1A pins of the motor shield.

<img src="../Pictures/wires.jpg" width="400px"/>

<img src="../Pictures/assembly8.jpg" width="400px"/>

### Results
- At the end, the result look like this:

<img src="../Pictures/assembly9.jpg" width="400px"/>