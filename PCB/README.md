<div align="center">
  <h1>DSpi Mainboard PCB</h1>
</div>

<div align="center">
  <img src="https://i.imgur.com/5myap0f.png" alt="Image of DSpi Motherboard" width="80%">
</div>

The DSpi PCB has a custom mainboard pcb that provides power, audio and controls to the CM5 module. This must be ordered from a PCB fabricator, and I used and recommend JLCPCB for this.
To ensure all trace impedances are correct, for the usb and display lines, you **must** order the board with the **JLC04161H-7628** layer stackup, AND **1.6 mm** thickness. I also recommend getting assembly on at least the top side, as most components used are SMD, and hard to hand solder. My recommended settings for jlcpcb are shown below:

<div align="center">
  <img src="https://i.imgur.com/nAFveAb.png" alt="Image of JLCPCB Settings" width="50%">
</div>
<p align="center">Recommended JLCPCB Settings (All other values default)</p>
