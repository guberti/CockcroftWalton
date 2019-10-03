# 40 kV 10 mA Cockcroft-Walton Multiplier
To power a Farnsworth-Hirsch fusor me and some other [@EastsidePreparatorySchool](https://github.com/EastsidePreparatorySchool) students are building, we calculated we would need 10 mA of DC current, since the amount of radiation produced is proportional to the **square** of the voltage.

In this repo you can see the files needed to edit and order these circuit boards yourself. They are in EAGLE CAD format, and a ZIP file accepted by circuit board makers is also provided. 

The Cockcroft-Walton multiplier here is a two-stage full-wave multiplier. It is intended to be powered by a neon sign transformer that supplies 24 kV peak-to-peak AC at 30 mA in alternating phases. These are pretty cheap, and can be had on Ebay for ~$150. Note that you will need to remove the safety features of the NST before it can power these multipliers.

The circuit board, as printed, transforms this into +35 kV DC at 10 mA, though I intentionally installed the diodes backwards in my multiplier so it produces -35 kV instead (this is needed for deuterium fusion, since these ions are positively charged).

<img src="https://i.imgur.com/d0HrIWG.jpg">
<p align="center"><i>Two stages of the soldered board. Blue jumper wires are present to stop the capacitors from building up charge.</i></p>
<img src="https://i.imgur.com/F1Mf1QZ.png">
<p align="center"><i>The circuit board in EAGLE CAD</i></p>
<img src="https://i.imgur.com/109R7Kb.jpg">
<p align="center"><i>Voltage monitoring system for the CW circuit board. Note the level-shifted voltage dividers.</i></p>
