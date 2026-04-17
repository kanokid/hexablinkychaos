# HexaBlinkyChaos

HexaBlinkyChaos is a amped up blinky board featuring 3 CD4017 ICs, one for normal mode (it acts like your typical blinky) and 2 for chaos mode (which has one for all odd LEDs and one for all even LEDs. with reset pins for even more chaos!) It has 10 LEDs like normal, and uses the NE555P IC for clock timing. It also includes an optional USB-C port for your convenience.  (because why not) It uses 3 SPDT slide switches in total, 1 is to change between normal and chaos mode and the other 2 are for chaos mode, letting you run only evens or odds with one, or both with the last switch. I also have 2 of the CD4017 ICs (for chaos mode) set to count to 5 instead of 10. 1N4148 diodes are used to prevent backfeeding into the ICs since 2 ICs share 1 LED, but only is used at a time.

### Pictures:
Schematic:
<img width="1502" height="903" alt="Screenshot 2026-04-16 220010" src="https://github.com/user-attachments/assets/79304b0c-872c-4b01-b276-44cb812ce4c0" />

PCB:
<img width="1038" height="861" alt="Screenshot 2026-04-16 220157" src="https://github.com/user-attachments/assets/d1d9c597-14b8-4c71-9e2f-fb0ce576aa6d" />

PCB Render:
<img width="998" height="839" alt="Screenshot 2026-04-16 220850" src="https://github.com/user-attachments/assets/c9e97a31-722b-438c-8875-9984a88e17ba" />
