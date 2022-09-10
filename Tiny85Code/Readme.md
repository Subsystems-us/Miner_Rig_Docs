These are the compiled code for the Tiny85 with the 16MHz PLL clock and D3 as the LED pin so they will work with the schematic.

Set the fuses of the Tiny85s to:
L:0xF1
H:0xDF
E:0xFF

Instead of using the automatic I2C address assignment in the original code, I hard coded the addresses. The address is the same number as in the file name. I sometimes had issues with the automaticc system, so I decided to hard code them in.

