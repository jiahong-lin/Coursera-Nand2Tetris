#### Project 1: Boolean logic

**Chips:** 

Nand、Not、And、Or、Xor、**Mux、DMux**

Not16、And16、Or16、Mux16、Mux4Way16

**Or8Way**、DMux4Way、DMux8Way



**Implementation:** 

Nand (**primitive**): Not (A And B)

Not: Nand (in, in)

And: Not (Nand (a, b))



Not + And -> Or (*DeMorgan*'s Law)

Not + And -> Xor、Mux、DMux



Mux -> Mux4Way

DMux -> DMux4Way

DMux4Way + DMux -> DMux8Way