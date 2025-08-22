<div align="center">
  <img src="https://i.imgur.com/778nG7R.jpeg" alt="Lower DSpi" width="80%">
</div>

## DSpi
The DSpi is a Dual Screen Linux handheld powered by a Rasberry Pi Compute Module 5, designed primarily for DS emulation. The device features a 5000mah amp battery, Xbox pattern controller with dual analog sticks, Dual 480p DSI touchscreens, Stereo speakers and a DAC + Headphone amp. I reccomend using the Rasbian system image provided in the above files, featuring retropie for single screen systems, and melon DS for true dual screen DS emulation (System image coming soon).

## System Specifications

- Uses any Pi CM5 module (however the CM5 lite 8GB wifi is highly recommended) with 4 A76 cores at 2.4GHz.
- 2*800x480 Waveshare IPS displays, both touchscreen.
- Stereo speakers, using 2*MAX98357 IC amplifiers, over the I2S interface.
- Headphone output, using the PCM5102 DAC + PAM8908 Headphone AMP.
- 5000 Mah LiPo battery, with 5V 3A charging using the BQ25890 1S BMS IC.
- Full size controller using RP2040, and the GP2040CE firmware, including dual analog 3ds slide pads.
- Full 3d printable chassis (In FDM!!! - Tested using neptune 4 pro, using 30% speed for hinges), using GBA SP hinges.

## Other notes
This is still a mostly experimental project, and could still use a lot of work, especially on the software side in improving the user experience. Personally if i was looking to emulate DS, I would get either a 3ds, or one of the new android emulation handhelds, however this has still been a fun project to work on. Future plans for this include swapping the main screen to the new 5" touch display 2, and making some pcb adjustments to reduce the device width.
