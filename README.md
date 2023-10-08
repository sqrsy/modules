# What is it?

This folder contains Eurorack modules (PCBs and panels) that I designed. They are all open to use, but you must make any derivatives open too. If you use them commercially, please donate 10% of profits to a charity nearby you.

I will add detailed part lists and assembly instructions if and when I make them.

# Modules

* calculate: uses a few op-amps to perform basic operations like attenuversion, addition, and comparison.
	* Parts: thonk jacks, thonk 50k pots, {1k, 10k, 100k} resistors, tl074 op-amps, 3mm LEDs, 10-pin power.
	* Note: this is an imperfect module. It is missing bypass capacitors.

* logic: two sets of 2-input, 3-output logic gates: or, and, xor.
	* Parts: thonk jacks, {5k, 150k} resistors, 3mm LEDs, 4030 IC, 4071 IC, 4081 IC, 16-pin power.
	* Note: this is an imperfect module. It is missing an input comparator and an output buffer, and has untied pins on the unused logic gates.

* rasa6: a generic 1-input, 2-parameter, 2-output Arduino Beetle Eurorack module shield with optional DAC.
	* Parts: thonk jacks, thonk 50k pots, {150k, 220k} resistors, mcp4822 (optional), 16-pin power.

* rectified-mult: a 9-jack mult where 4 of the jacks apply some rectification to the signal.
	* Parts: thonk jacks, 1k resistors, diodes, full-bridge rectifiers, 3mm LEDs.

* stereo-mult: two separate 6-jack mults that each can split a stereo signal into left and right channels.
	* Parts: thonk jacks, 1k resistors, 3mm LEDs.

* switched-mult: a 9-jack mult that can route a 3-jack mult to one of two different sets of 3-jack mults.
	* Parts: thonk jacks, thonk sub-mini switch.

# Disclaimer

All files are provided without any guarentee. If you notice a mistake, please submit an Issue and I will fix it.