# Programming the DSpi motherboard
Some parts of the DSpi mainboard require programming after assembly. The onboard MCU (STM32) is used to control the BMS Chip settings, and must be flashed with the provided code for the mainboard to function. To do this, you need an ST-LINK, and a computer with STM32CUBEIDE - This may not be required, testing whether I2C can be set by CM5.
# Programming the DSpi controller
The DSpi controller uses the GP2040-CE architecture. To install the controller firmware, follow the setup instructions on the gp2040-ce website, seen here: https://gp2040-ce.info/installation. Use the boot button labeled on the mainboard. Once the GP2040 firmware is installed, open the web config, and change the input mode to directinput, and go to addons and enable both analog sticks, with inverted Y for both sticks. The instructions for this are here: https://gp2040-ce.info/web-configurator.
# Flashing the DSpi OS image
Use BalenaEtcher or a similar program to write the included image to an SD card, then insert into the DSpi SD slot before boot. If the correct OS is not installed and inserted, both screens will remain black after boot.
