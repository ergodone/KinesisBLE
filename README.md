
# Wireless Kinesis Advantage BLE (Bluetooth Low Energy)

Turns the [Kinesis Advantage Keyboard](https://www.kinesis-ergo.com/shop/advantage2/) keyboard into a wireless BLE keyboard with a few extra features. Built with Adafruit's nRF52 Feather Express Arduino boards.

# About this fork

Adds support for the Kinesis Advantage or Professional keyboard to the original KinesisBLE design.  Also makes the PCB slightly smaller which should help minimize cost (specifically for JCLPCB).  The redesign has been done in open-source and free Kicad which should help future development.

# Firmware

The firmware in this repository it not what you want to use.  It's mikewudev's original firmware and is limited compared to ZMK.  

See the [ergodone ZMK repository](https://github.com/ergodone/zmk) for the ZMK firmware. Note there is a more current (and much preferred) ZMK firmware module that supports ZMK studio [ZMK-kinesis repository](https://github.com/ergodone/zmk-kinesis) and builds through GitHub actions (no need to install a build environment). This module is still in actively being worked on (as of 2024-11-08).

# A note on Function Keys

The original function keys are not particularly reliable nor responsive.  A PCB designed to use mechanical switches is documented here: **[Bluelightning32 Function Key Replacement](https://github.com/bluelightning32/kinesis-fn)**  This is not required for the KinesisBLE project but is a worthwhile upgrade if you are doing modifications.


# Wireless Kinesis Advantage BLE (Bluetooth Low Energy)

Turns the [Kinesis Advantage Keyboard](https://www.kinesis-ergo.com/shop/advantage2/) keyboard into a wireless BLE keyboard with a few extra features. Built with Adafruit's nRF52 Feather Express Arduino boards.

For instructions, see the **[wiki](https://github.com/sysdevmike/KinesisBLE/wiki)**. For more details on the build check out the **[project](https://hackaday.io/project/161578-wireless-ble-kinesis-advantage-custom-controller)**.


## Many thanks to

- [Yin Zhong](https://summivox.wordpress.com/2016/06/03/keyboard-matrix-scanning-and-debouncing/) - Explains a better way to handle debouncing.
- [Stapelberg](https://michael.stapelberg.ch/posts/2018-04-17-kinx-keyboard-controller/) - Double mention as I ported his debouncing used in his KinX controller to Matt's firmware.
- [Matt Vilim](https://github.com/mattvilim/FeatherCtrl) - New firmware is a fork of his FeatherCtrl project.
- [Adafruit](https://www.adafruit.com/product/3406) - Great documentation, libs and support.
- [afriggeri](https://github.com/afriggeri/kb) - The original firmware borrowed heavily from his [Blanck Keyboard](https://medium.com/@friggeri/the-blanck-keyboard-24afe12e81a) project.
- [Stapelberg](https://michael.stapelberg.de/posts/2013-03-21-kinesis_custom_controller/) - Michael Stapelberg's custom controller inspired this project. His PCB routing was inspirational.
- [Humble Hacker](http://humblehacker.com/blog/20100720/hacking-the-kinesis-contoured-keyboard/) - Detailed write-up helped me understand the keyboard matrix.
- [PCBgogo](http://www.pcbgogo.com) - All the boards were made by these guys. Fast turn-around. 
