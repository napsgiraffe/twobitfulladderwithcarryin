<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
This design implements a 2-input adder with LED indicators. 
Five DIP switch inputs (A0, A1, B0, B1, and carry-in) feed
a bunch of gates. The output is displayed on three LEDs (S0, S1, and Carry Out). 
Five additional LEDs mirror the individual input states.

(Has the same output as a full 2-bit adder, sorry didn't want 
to type out the whole thing just for this quick session thing)

## How to test
(ignore this i didn't update it. Just test it how you would a regular adder
So try A0 + B0, A1 + B0 + Cin, etc etc)
1. Toggle ui[0] (Switch A) and ui[1] (Switch A0).
2. Observe uo[0] (red LED) for the NAND output.
3. uo[1] and uo[2] show the current input states.
4. Verify all four rows of the truth table above.
## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
