# Programming the DSpi motherboard
Some parts of the DSpi mainboard require programming after assembly. The onboard MCU (STM32) is used to control the BMS Chip settings, and must be flashed with the provided code for the mainboard to function. To do this, you need an ST-LINK, and a computer with STM32CUBEIDE - This may not be required, testing whether I2C can be set by CM5.
