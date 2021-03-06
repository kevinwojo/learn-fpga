Episode VII: Linear execution flow, adding `reg <- reg OP imm` ALU instructions
----------------------------------------------------------------------------
![](Images/FemtoRV32_design_2.jpg)

Let us now introduce the ALU operations that take immediate values. To
do that, as shown in the schematic, we insert a mux before the
second ALU input. This mux selects either the second output register
from the register file or the decoded immediate value. It is driven by
an additional signal generated by the instruction decoder. 

We have implemented 2 out of 7 instructions, let us continue...

[Next](FemtoRV32_VIII.md)