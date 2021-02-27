# KinesisBLE with Kinesis Professional/Advantage compatible PCB



These are KiCad files for the KinesisBLE PCB.  The PCB has been made slightly smaller from mikewudev's original design while still maintaining the same connector locations. There is also the option of using the PCB in a Kinesis Professional (with the flex PCB "fingers") by using Molex 39-53-2134 on J2 and J7.  For Kinesis Advantage a Molex 39-53-2135 or Cvilux CF01-13-1V00 is used on J5 and J6.

A couple issues with the layout:
1) the slots for the tabs need to extend 1mm closer to the center of the board.  ![Image of offset](taboffset.jpg)
2) if you use a jumper for the power button led it may interfere with the usb plug. ![Image of usb cable covering power button led](kinesisble.jpg)
3) the usb cable connector may need to be trimmed down to avoid touching the bottom half of the case. ![Image of trimmed usb connector](kinesisble.jpg)

The board has been tested and is currently in use using ZMK firmware.
