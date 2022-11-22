# Lego-Workshop
Ziel dieses Lego-Workshops ist es Kinder in einen Beteiligungsprozess zu integrieren. Theoretisch wäre das Konzept auch mit Erwachsenen durchführbar. Das coole an dem Konzept ist, dass die Meinung jeder Person durch Lego ausdruck findet. Die Teilnehmenden (TN) bauen nach einer Einführung ihre eigene perfekte smarte Stadt der Zukunft. Die Teilnehmenden werden Schritt für Schritt durch die verschiedenen Stufen der Bauphasen geleitet und am Ende gibt es eine große Smarte Stadt der Zukunft.



---

## Parts you have to buy
- Eine Menge Lego oder anderer Klemmbausteine


## 3D-printed Parts
Wir haben aus dem 3D-Drucker Stadteilobjekte ausgedruckt und dafür uns bei [Thingiverse](https://www.thingiverse.com/search?q=church&page=1&type=things&sort=relevant) bedient. Diese 

## Tools you need
- side cutter
- needle nose pliers
- crimping tool
- solder iron (we use the Pinecil from pine64)
- wire stripper
- wood glue
<img src="images/tools.jpg" width=300px alt="tools">


## Preparation
Bereite den Raum so vor, dass Du Gruppentische für die einzelen Teams hast an denen sie bauen können. Es braucht einen großen Tisch für die Bautsteine an denen sich die Teilnehmenden bedienen können. 
Zeichne ggf. [Flipcharts](https://github.com/MINT-Labs-Regensburg/SmartCity-Lego-Workshop/blob/main/Fotodokumentation_FutureRegensburg_NaWo.pdf) vor oder baue Dir eine PowerPoint, um die einzelen Schritte an die Wand werfen zu können.

## Built

### Wooden parts
- Use wood glue as shown in the picture; the front panel should not be glued (this is for maintenance)
- put in the two switches into the front panel
- attach the USB-PD housing with 2 screws M3x6 countersunk with nuts
- Prepare the PC fan: fan grille, PC fan (sticker should look through the grille), spacer, filter
<p float="left">
  <img src="images/woodenParts.jpg" width=300px alt="woodenParts" />
  <img src="images/frontpanel.jpg" width=300px alt="frontpanel" /> 
  <img src="images/PCfan.gif" width=600px alt="PCfan.gif" />
</p>

### Electrical Installation
- after soldering the cables (twin strand as in [1]) put in the USB-PD converter and fix ith with the zip tie
- attach the cable lugs of the twin strand wirde [2] to the barrel connector
- solder the twin strand wire [4] to the LED band. Notice the polarity of the solder pads and the directionality of the LED-band itself!
- connect the remaining cables (positive side, red) from the LED band and the PC fan to the respective switches
- put all cables (positive and negative ones) into the two electrical installation clamps, one is for negative (GND) and one for positive (24V). On the positive clamp you should have the barrel connector (red), the switches, the USB-PD converter (red). On the negative one you should have the barrel connector (black), the LED-band (black), the PC-fan (black) and the the USB-PD converter (black)
<p float="left">
  <img src="images/cables_1.jpg" width=350px alt="cables_1" />
  <img src="images/cables_2.jpg" width=350px alt="cables_2" /> 
  <img src="images/cables_3.jpg" width=350px alt="cables_3" />
  <img src="images/cables_4.jpg" width=350px alt="cables_4" />
  <img src="images/solderLED_1.jpg" width=350px alt="solderLED_1" />
  <img src="images/solderLED_2.jpg" width=350px alt="solderLED_2" />
  <img src="images/solderLED_3.jpg" width=350px alt="solderLED_3" />
</p>


### Metal Toolbox
- Prepare the metal toolbox as described in the file metalCaseDrilling\drillings.svg


### Finishing
- Put the whole insert into the metal toolbox
- drill the four corner holes (diameter 3-3.2mm) through the wooden parts
- attach the wooden insert by four screws M3x8mm using 8 washers and 4 nuts
- Put the barrel connector into place and screw it
- Close the front panel, check that no cables are cut or bruised
- Lock the front panel with the two screws M3x10 with two washers M3 and two nuts
- Connect the power supply; connect a solder iron to the USB-C connector from the USB-PD converter
- Check functionality of fan, LEDs, solder iron
- Using double-sided adhesive tape, attach the remaining MDF-plate to the lit; this is used as a pad inside the lit for soldering




---

## Credits
- Vielen Dank an [R_next](https://www.regensburg.de/r-next)für die gemeinsame Zusammenarbeit


## Copyright and Authorship
 [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) - [MINT-Labs Regensburg e.V.](https://www.mint-labs.de).
