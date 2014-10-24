# Tact Hardware

Tact sensor schematics - electronic circuits that enable experiments with capacitive sensing.

----

This project belongs to the following repositories:

* **[Tact Arduino sketches](https://github.com/StudioNAND/tact-arduino-sketch)** and **[Tact Arduino library](https://github.com/philippschmitt/tact-arduino)** (by Philipp Schmitt) to drive circuit interface. Those scripts are for handling serial requests and serving sensor data.
* **[Tact for Processing](https://github.com/StudioNAND/tact-processing/)** for retrieving and processing sensor data in an easy manner.

## Circuit

![Basic Tact Sensor Circuit](https://raw.githubusercontent.com/StudioNAND/tact-hardware/master/tactA_pcb/assets/tactA-pcb-single-schematics-noframe.png)

The Tact circuit is based on Mads Hobye's capacitive touch [Arduino Tutorial](http://www.instructables.com/id/Touche-for-Arduino-Advanced-touch-sensing/step1/Components-neded/). You will need the following components to set up a basic version:

* 1× 1N4148 diode
* 1× 10mH coil

Condensators

* 1× 100pF
* 1× 10nF

Resistors

* 1× 3,3k
* 1× 10k
* 1× 1M

The following [Frizing](http://fritzing.org/home/) sketches illustrate how to set up a Tact sensor. Each of them are kept as simple as possible, essentially only requireing a breadboard and jumper wires to hookup everything to the Arduino.

#### Single Sensor Setup

![Breadboard setup for Tact single sensor](https://raw.githubusercontent.com/StudioNAND/tact-hardware/master/tactA_breadboard_single/assets/tactA-breadboard-single-fritzing.png)

[Download](https://github.com/StudioNAND/tact-hardware/raw/master/tactA_breadboard_single/tactA_breadboard_single.fzz) the Fritzing sketch - or browse the corresponding [project folder](https://github.com/StudioNAND/tact-hardware/tree/master/tactA_breadboard_single) in this repository.

#### Multiplexed Sensor Setup

![Breadboard setup for Tact Multiplexed sensor](https://raw.githubusercontent.com/StudioNAND/tact-hardware/master/tactA_breadboard_multiplex/assets/tactA-breadboard-muliplex-fritzing.png)

[Download](https://github.com/StudioNAND/tact-hardware/raw/master/tactA_breadboard_multiplex/tactA_breadboard_multiplex.fzz) the Fritzing sketch for detailed investigation - or check the corresponding [project folder](https://github.com/StudioNAND/tact-hardware/tree/master/tactA_breadboard_multiplex) in this repository.

### Source
All source files that are required to modify and extend circuits are contained within th download and also available on [github](tree/master/src).

### Questions?
Any questions or feedback? Contact me on [twitter](http://www.twitter.com/steffen_fiedler). For bug reports, please use the [issue tracker](issues).

## Who made this?
The material in this repository has been developed by [Studio NAND](http://www.nand.io). It’s based on many smart ideas – so cheers to everyone who contributed her/his time to investigate capacitive technology! Special thanks to the team around [Ivan Poupyrev](http://www.ivanpoupyrev.com/) for all the research within this field and [Mads Hobye](http://www.hobye.dk/) for his [Arduino tutorial](http://www.instructables.com/id/Touche-for-Arduino-Advanced-touch-sensing/) about advanced touch sensing. All of that has been a big help and inspiration.

## Copyright
Copyright (c) 2014 [Studio NAND](http://www.nand.io). Licensed under the GNU Lesser General Public License. See *license.txt* for further details.

Any example code is released into the public domain.
