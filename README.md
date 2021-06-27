# Datapath 16 Bit
This design 16 bit datapath design. In this design, ADD, AND and LDR command are run.

## Transactions and Project Simulation
I run 4 command in my project. This commands exist in ROM.

LDR R1, [R0, #0] = 0000010 001 000 000  0x0440

LDR R2, [R0, #1] = 0000010 010 000 001  0x0481

ADD R3, R1, R2 = 0000000 001 010 011  0x0053

AND R4, R1, R2 = 0000001 001 010 100  0x0254

Then, I inserted some values into RAM. LDR commands load values from RAM to registers.


