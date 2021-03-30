## Notes
* Enclosure needs supports (my design was lazy in that regard!)
* Need:
  * 4x 7mm M3 bolts
  * 4x M3 square nuts
  * 1x right-angle tactile switch (~7.6 x 6.4mm on the face iirc - anything close is fine, as it's largely hot glued in place)
  * Hot glue
* Only supports red-PCB ILI9341 TFT + Seeduino Xiao.
* Does not include neopixel or encoder support. Amend the code as needed.

## Installation
* Run wires between the Xiao and the TFT as per hookup diagrams (short cables; maybe 3cm max?) + The tactile switch (maybe a little longer, so it can reach the side of the back casing) -- tactile switch goes between RESET (tiny pad) and GND (either the other tiny pad, or the main GND pad if that's easier)
* The Xiao should press-fit into the slot in the back of the case, make sure it's as far into the slot as possible, else it will clash with the back of the TFT. Apply a little hot glue to secure if wanted (but really it should be held in by the back of the screen).
  * Make sure cables run in a way that they won't end up between the back of the Xiao, and the TFT; else they'll get crushed.
* Pop the tactile switch into place, and hot glue to secure it.
* With the xiao in place, sit the TFT onto the back case, ensuring no cabling gets trapped
* Add the front case into place, and secure with M3 nuts and bolts.
* Optionally add the screw plugs for a cleaner look (note that they may need scaling/sanding etc depending on your printer's tolerances)
