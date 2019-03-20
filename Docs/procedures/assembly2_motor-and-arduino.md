<!--# Correction
* <span style="color:red">Put **/procedures** and **/pictures** folders in **/docs**.</span>
* <span style="color:red">Exact same remarks as the other procedure.... please read them!</span>-->

# LPro AIT 2019 - TP1 - Assembly procedure : motor to the arduino

- Names
    - Loris ARNAUD
    - Augustin GARES

The 7th of March of 2019

## 1. Hardware list

1. EMG30 motor with blue support assembly X1

     <img src="../Pictures/assembly5.jpg" width="400px"/>

2. Arduino Uno X1

    <img src="../Pictures/arduino.jpg" width="400px"/>

3. Arduino shield - Pololu DRV8835 Dual Motor Driver with jumper X1

    <img src="../Pictures/shield-motor.jpg" width="400px"/>

4. Laptop X1

    <img src="../Pictures/laptop.jpg" width="400px"/>
    
5. USB câble X1

    <img src="../Pictures/USB-cable.jpg" width="400px"/>

## 2. Tools

1. Flathead screwdriver X1

    <img src="../Pictures/screwdriver.jpg" width="400px"/>

## 3. Assembly procedure : motor to the arduino

### First step
    Download the arduino program motor_control_open_loop on the laptop.

1. 
    <img src="../Pictures/laptop.jpg" width="400px"/>

### Second step
    Download the DRV8835MotorShield librarie into the arduino IDE.

### Third step
    Wire the laptop to the arduino with the USB cable.

1. 
    <img src="../Pictures/USB-Arduino.jpg" width="400px"/>

2. 
    <img src="../Pictures/USB-PC.jpg" width="400px"/>

### Fourth step
    Download the software on the arduino UNO and verify if the LED blinks every 2 secondes on the arduino. After, unwire the USB cable from the arduino and the laptop.

### Fifth step
    Put the jumper on the motor shield on the VOUT pin, like on the picture.

1. 
    <img src="../Pictures/shield-motor-with-jumper.jpg" width="400px"/>

### Sixth step
    Pin the arduino shield on the arduino. The Vcc pin of the shield have to be on the 5V pin of the arduino. Verify that pins of the shield are on rights pins of the arduino.

1. 
    <img src="../Pictures/assembly6.jpg" width="400px"/>

2. 
    <img src="../Pictures/assembly7.jpg" width="400px"/>

### Seventh step
   Plug the red and black wires of motor in the M1B and M1A pins of the motor shield.

1. 
    <img src="../Pictures/wires.jpg" width="400px"/>

2. 
    <img src="../Pictures/assembly8.jpg" width="400px"/>

### Results
    At the end, the result look like this:

 <img src="../Pictures/assembly9.jpg" width="400px"/>