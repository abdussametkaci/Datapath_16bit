# Datapath 16 Bit
This design 16 bit datapath design. In this design, ADD, AND and LDR command are run.

## Transactions and Project Simulation
I run 4 command in my project. This commands exist in ROM.

LDR R1, [R0, #0] = 0000010 001 000 000 -> 0x0440

LDR R2, [R0, #1] = 0000010 010 000 001 -> 0x0481

ADD R3, R1, R2 = 0000000 001 010 011 -> 0x0053

AND R4, R1, R2 = 0000001 001 010 100 -> 0x0254

Then, I inserted some values into RAM. LDR commands load values from RAM to registers.

## ROM
![](https://abdussametkaci.github.io/Datapath_16bit/img/rom.PNG)

## RAM
![](https://abdussametkaci.github.io/Datapath_16bit/img/ram.PNG)

Firstly, program counter is enabled and then, the clock signal is
triggered. The command at the address indicated by the program
counter is executed and the next command is passed.

After all the commands in the program are
executed, the data inside the registers are
shown.

![](https://abdussametkaci.github.io/Datapath_16bit/img/registers.PNG)

# Datapath Components
## PC
![](https://abdussametkaci.github.io/Datapath_16bit/img/pc.PNG)

## ALU
![](https://abdussametkaci.github.io/Datapath_16bit/img/alu.PNG)

## Memory
![](https://abdussametkaci.github.io/Datapath_16bit/img/mem.PNG)

## Register File
![](https://abdussametkaci.github.io/Datapath_16bit/img/register_file.PNG)

## Control
![](https://abdussametkaci.github.io/Datapath_16bit/img/control.PNG)

## All Design
![](https://abdussametkaci.github.io/Datapath_16bit/img/design.PNG)
