This folder contains the platformIO src files for both the generic version (with VCO, LFO, ADSR etc.) and the midi2 cv version (using the USB C port as a midi device). 

The midi to CV codebase is based on https://github.com/nyannkov/nano_midi and is quite different than the generic version since it is relying on build scripts. It should be feasible to merge the two projects to a single project where the midi function is integrated in the menu system - let me know if you succeed ;)

The python scrips were used to generate icons, look up tables (LUT) and menus.
