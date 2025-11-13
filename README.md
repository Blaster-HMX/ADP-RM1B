# ADP-RM1B
Original adapter for Hi-Lo Systems ALL-03/ALL-07... universal programmers, exact PCB clone.

This adapter allows testing of SIMM72 DRAM memory modules.

Limitation: cannot test double-sided memory modules due to missing #RAS1/3 signal.
Workaround: add a wire to connect pin 6 of the ZIF socket to pins 33 and 45 of the SIMM72 test socket.

This project includes:
- Gerber files in zip
- Eagle 7 CAD schematic/board files in zip
- Schematic in pdf
