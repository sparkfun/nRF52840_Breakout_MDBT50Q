SparkFun Board Variant Definitions for Adafruit nRF52 Arduino Core
==================================================================

### Installation Instructions

To add SparkFun nRF52840 board support to the nRF52 Arduino core, one file (boards.txt) needs to be modified, and one new folder (variants/sparkfun\_nrf52840\_mini) needs to be copied in.

First, navigate to your Adafruit nRF52 core installation. If you installed via the board manager it'll probably be in one of these folders:

* Windows: %LOCALAPPDATA%\Arduino15\packages\adafruit\hardware\nrf52\<version>
* OS X: ~/Library/Arduino15/packages/adafruit/hardware/nrf52/<version>
* Linux: ~/.arduino15/packages/adafruit/hardware/nrf52/<version>

If you installed the core manually into your Arduino sketchbook, it'll be in a "hardware/adafruit/nrf52" in there.

Then **open boards.txt**. Scroll to the bottom and **paste the contents of sparkfun\_boards.txt** into the bottom of that file.

Then copy the contents of the "variants" folder in this directory into the "variants" folder of the original directory. Nothing should be overwritten, but a new "sparkfun\_nrf52840\_mini" directory should be added in.

### Directory Contents

* sparkfun\_boards.txt -- Additional board definitions for SparkFun nRF52840 boards 
* variants/sparkfun\_nrf52840\_mini -- SparkFun Pro nRF52840 Mini board (pin, LED, serial port) definitions. 
