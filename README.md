zx Spectrum keyboard intended for a Harlequin project. 

This implementation provides
o Layout for a cherry keyswitches
o Power + optional utility LEDs for hard drive and Floppy disk. (you need to provide these signals)
o Digital logic/diode logic for composite keys as used on the spectrum+ keyboard
o Optional header for remote cursor keys. 

Notes:
If you are using this on an original speccy for a keyboard with a long wire run, you will need to add buffering closer to the spectrum.
This should be something like a 74LS245 connected to the 8 pin keyboard header. For Short wire runs this wont be a problem. 

this will not be nessesary for a Harlequin kit which uses Transistors to buffer the signals from the CPU. 
