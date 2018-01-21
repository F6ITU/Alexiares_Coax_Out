# Alexiares_Coax_Out V1

Kicad files

OpenHPSDR RX and TX rear panel crowbar (coax input and output)

##Branch Master
-----------

  Please do NOT use this repository.
  Master is the main development trunk and, for this reason, 
  is in a perpetual unstable state. Use the last branch instead
-----------

For more informations, please refer to 

https://wiki.electrolab.fr/Projets:Lab:2017:Peripheriques_Angelia

This board could be cut in half and shielded

Input are fully compatible with Alexiares/Alexandrie output

TX antenna relays are rated at 150 W PEP (300 W maximum)

It also could work with DC2PD I2C interface 
and it's forked version AlexI2C

3D image of the board are stored on this repo

RX_Ant dwn.jpg

RX_Ant_up.jpg


Bom is available in CSV format

Schematics, pcb design, modules and libs are in Kicad format

Gerber files are fully compatible with Protel 4.6 format

Board's dimensions are oversized to fit the 5x10 and 10x10cm 

size of all board of the Hermes project under Kicad: 

* Alexandrie (Ἀλεξάνδρεια), Alexiares SPI interface
* Alexi2C ( Ἄλεξις), Alternate Alexiares I2C interface
* Alexiares_lpf (Ἀλεξιάρης) Alexiares low pass filter
* Alexiares_hpf (Ἀλεξιάρης) Alexiares high-pass filter
* Alexiares_Coax_Out (Ἀλεξιάρης ) Alexiares antenna switch boards
* Télémaque (Τηλέμαχος),  SSPA U/V/C°/Refl/FWD sensor for the Mentor board 
* Mentor (Μέντωρ) Micro-controler unit(MCU) and security module controling Telemaque informations
* Ulysse ou Odysseus (Ὀδυσσεύς), medium power reflectometer for the Telemaque/Mentor set
* Themis (Θέμις), low power bidirectionnal reflectometer with pre-distorsion (pure signal) output
* Aiôn (αἰών), 10 MHz low drift, low phase noise clock (general purpose)
* Hébé (Ἥβη), EER control system for high efficiency power amp
