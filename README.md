# Wheelchair-Dragon
Fire breathing dragon built on an electric wheelchair remote controlled by wireless gamepad.

This is a work in progress.

Currently using a Dimension Engineering Sabertooth 2x32 dual motor driver to drive the wheelchair motors.  The main controller is a Teensy 4.1 using the host USB port for the wireless dongle of a Logitech F710 gamepad.  The Teensy 4.x audio board is also used to play dragon sounds from SD card.  MOSFET switch boards will control various functions.  Linear actuators controlled by H-Bridge boards are used to move things like neck, wings, etc. on the dragon.  Currently considering using proportional soenoid valves for the dual accumulated poofers (fire effects).  These take 0-10VDC as input.  Will test with PWM to 0-10V and I2C DAC boards.
