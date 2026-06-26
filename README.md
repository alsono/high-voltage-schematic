# WARNING: this doohicky is VERY dangerous please do not attempt to recreate this yourself in the absence of a professional.
## What this is
Voltage multiplier that can convert 12V DC into 6.3KV-8.4KV AC
## How it works
<img width="923" height="516" alt="image" src="https://github.com/user-attachments/assets/3d5b5863-4f00-4960-8da8-00ba18a51494" />

- the two transistors convert the dc current from the source into
ac, the capacitor sets the frequency.
in the transformer the ac voltage is converted to 27-33 times the original the original (from 12 to 300-400) depending on your transformer.
afterwards the voltage is stepped up using the capacitor voltage mult circuit that is 100% overkill lmao. and then passed into the final output.
## what its used for
- lighter
- light
- cool thing to display
- arcing
## what this is ISN'T used for
- home defense
- taser (using a battery to make this portable would make it qualify as a stun gun aka illegal EVEN THOUGH IT DOESN'T STUN)
## notes for assembly
- you may choose a transformer yourself just don't go too high
- you will need somewhat of a high current source, if you hook it up to a battery make sure to use high current resistors (2W should work)
- this thing might just combust
- do NOT make a pcb for this use a development board
- check out the BOM for what you need
- you may replace the 15k resistor with a 30k potentiometer to configure the speed
