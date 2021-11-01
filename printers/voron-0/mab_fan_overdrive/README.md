Voron 0.1 Mini Afterburner Part Fan Overdrive
=

Existing Design
==
The part fans on the V0.1 are sinking PWM, meaning that the supply voltage is permenantly connected to the motors and the negative, or gound is PWM switch modulated.

This means that the same connector circuit can drive different voltage fans, by simlpy changing the positive supply voltage.

BigTree don't seem to publish the current rating for the CNC fan switching, but the mini SKR e3 V2 uses AO3400A mosfets for it's fan switching which are good for 5.7 amps. Althouth I am not sure what current the rest of the circuit provides, this should be sufficient to drive 1/2 dozen fans, each drawing probably less than 100 miliamps.

Overdrive Design
===
This modification is to over-drive the existing mini afterburner part fans by roughly 10%, by boosting the voltage to them from 24 volts to 28 volts.



---
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg![](bed_location_left.png)

