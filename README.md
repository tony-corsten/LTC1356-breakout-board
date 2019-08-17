# LTC1356-breakout-board
# Overview
The LT1356 is a quad-input op-amp with high slew rate, fast settling time, low input noise and a wide supply voltage range, making it a fantastic ADC driver for ADCs with +/- 10V swings. It's a great choice for projects that want to conserve board space, but still need a lot of inputs (e.g., ADCs). [You can find the official documentation for the chip here.](https://www.analog.com/en/products/lt1356.html). This is a breakout board made in Kicad with dedicated headers for a power supply input and for input voltages. 

# Navigating this library
The main folder contains relevant Kicad files (.pro, .pcb, .sch). The `gerber` directory has a PCB-fabrication ready set of gerber files. The `library` directory has a custom footprint (.kicad_mod) that works for the SOP version of this chip. The chip schematic can also be found there. 
