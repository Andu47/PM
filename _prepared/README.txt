Prepared sheets (parts placed, not wired) - 2026-11-16

These files are kept out of the project folder because KiCad still had the
project open with unsaved work (Memory sheet). Copying them in while KiCad
is open could overwrite your work, or be overwritten by it.

To use them:
1. In KiCad: Ctrl+S in the Schematic Editor (saves your Memory sheet).
2. Close KiCad completely.
3. In a terminal:
     cd ~/Electronics/PM
     cp _prepared/*.kicad_sch _prepared/PM.kicad_sym _prepared/sym-lib-table .
4. Open the project again.

Files:
- io_decoding.kicad_sch    S1/S2 DIP switch + 2 pull-ups (decoder chips: after equations)
- serial_8251.kicad_sch    8251A, MAX232, DE-9 female, 4x 1uF, 2x 100nF
- parallel_8255.kicad_sch  8255A, keypad header, 3x 10k, LCD 16x2, contrast trimmer, backlight R, 100nF
- displays_leds.kicad_sch  8x 74LS373, 14 LEDs + 14x 330R, 6x SA39-11EWA, 6x 330R packs, 8x 100nF (A3)
- PM.kicad_sym + sym-lib-table   project library "PM" holding the 8251A symbol (not in KiCad libs)
