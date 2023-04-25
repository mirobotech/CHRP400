# CHRP4

CHRP4 (Common Hardware Robotics Project 4, rev. 0) KiCad schematic and PCB design files.

![Z30_0411](https://user-images.githubusercontent.com/4099144/234148584-2c3ee559-1f64-4043-ab50-033e1bba10ae.jpeg)

CHRP4 is a simple, versatile, and inexpensive microcontroller development system designed to help anyone make simple line-following, obstacle-sensing, or Sumo robots! CHRP4 is a robot-focused derivative of [UBMP4](https://mirobo.tech/chrp4), and was designed for learning or teaching PICmicro programming for robotic applications using either Microchip’s MPLAB X IDE or the cloud-based MPLAB Xpress IDE.

CHRP4 uses the [USB µC bootloader](https://hackaday.io/project/63204-usb-c-usb-pic-bootloader), which allows CHRP4 to appear as a mass storage drive for ease of programming. Simply drag and drop a compiled .hex file onto the ***PIC16F1459*** drive that shows up in your computer's device manager, and your program will start to run as soon as the file is transferred. The bootloader makes it possible to program CHRP4 using almost any kind of device, even enabling schools with 1:1 Chromebook programs to teach real C language microcontroller programming with Github integration.

The CHRP4 circuit board has a variety of simple I/O devices built-in so beginners can learn to code and make an assortment of different projects using just the parts on CHRP4 – no breadboarding, shields, or other modules are required. The on-board components allow CHRP4 to be built in a variety of configurations including: a minimal parts, education-focused trainer for specifically for teaching or learning microcontroller programming, a simple line-following robot, and, with the addition of an ultrasonic distance sensor module, an obstacle-sensing or Sumo robot.


## CHRP4 Hardware Features

- Microchip PIC16F1459 USB-capable microcontroller with 8k words of program FLASH (6k words free when using the USB bootloader), 128B of user FLASH, 1kB of RAM, 10-bit ADC, and a built-in temperature sensor
- optional SN754410 (or L293D) quad half-H bridge motor driver to run two DC motors in forward and reverse
- optional LF50AB low drop-out regulator for 6-12V battery operation
- 5 built-in pushbuttons
- 5 visible light LEDs
- 1 piezo beeper output
- optional 4-pin header for PORTC I/O pin expansion (designed for an HC-SR04 ultrasonic SONAR module, but can also connect to servos, optical sensors, NeoPixels, etc.)
- optional IR LED and phototransistor circuits integrated on three mini, break-away modules (one designed for line following robots, two designed for general floor sensing)
- optional IR demodulator for remote control decoding
- USB 2.0 type-C port for power and programming
- 6-pin ICSP (In-Circuit Serial Programming) header for PICkit-4

Find out more at [mirobo.tech/chrp4 ](https://mirobo.tech/chrp4), and see the CHRP4 description on [Hackaday](https://hackaday.io/project/190407-chrp4-usb-robotics-development-board).


## CHRP4 is Open

CHRP4 is open hardware and uses open source software – we want educators to have full access to the circuit, lesson materials, and code. The following permissions and conditions apply to CHRP4:
- the KiCad CHRP4 files stored in GitHub are open hardware licensed under the terms of the MIT license (except the mirobo.tech logo - see below). You are free to use and modify the CHRP4 files to make your own CHRP4 circuit boards.
- CHRP4 programs stored in GitHub are open source software licensed under the terms of the MIT license.
- CHRP4 learning materials on the mirobo.tech website are licensed under the terms of the Creative Commons CC-BY 4.0 license.
- the USB uC bootloader is open source and licensed under the terms of the GPL3.0 license by John Izzard.
- the mirobo.tech logo mark is a trademark of mirobo Technolgy and may not be used without prior permission.

## Can I buy a CHRP4?

CHRP4 boards, and kits are available at [mirobo.tech](https://mirobo.tech/chrp4).  
Bare CHRP4 printed circuit boards are also available from [OSHPARK](https://oshpark.com/shared_projects/rMynSTCb).
