# riscv-core-from-scratch
From raw 74HC logic gates on a breadboard to a complete RV32I processor core in Verilog.
> **Note:** Sorry if there are any typos or mispronunciations/grammatical errors—I won't be using AI to write the descriptions and notes here so that my learning process stays completely genuine.
This idea started from me liking computers, getting interested in knowing how it works. It started from knowing what VLSI is, then striking against the hobby of "breadboard cpu" building.  
## What is a "Breadboard CPU"?
A breadboard CPU is a CPU build on breadboards rather than on silicon ICs or Printed Circuit Boards, it combines components like logic gate ICs, registers, clocks and stuff or sometimes transistors with some other basic electronics( like resistors and capacitors) wired together on the breadboard using either jumper wires or mostly 22AWG wires cut at 90 degree clean angles.  
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/b80f8e62-2aa4-4f70-816b-f4c530dab0da" />  
*(Image: Example of a completed discrete breadboard computer architecture from youtube)* 


## Where did I start from?
I started from reading Morris Mano's Digital Design which I found really interesting, since I like maths(I figured I liked discrete mathematics while reading this).  
We start with binary numbers, how numbers are represented, gray codes, coding of numbers, conversions, map method then to where I am today logics and how to make an adder.

## Progress:

1. Learning to wire logic gate ICs & power rails  
   <img width="396" height="440" alt="image" src="https://github.com/user-attachments/assets/fd42b96e-4693-4b28-b43e-9c71842f23f5" />

   (*Image of me trying to figure out how the 74HC ICs are wired* )
3. Building a Half Adder (74HC86, 74HC08)  
   <img width="439" height="405" alt="image" src="https://github.com/user-attachments/assets/f539aebb-ec11-4286-affc-b5bf2fc14b2c" />
   
    (*Image of the half adder I made*)
5. Building a 1-Bit Full Adder (Cascaded stages + 74HC32 OR gate)  
  
    <img width="280" height="296" alt="image" src="https://github.com/user-attachments/assets/48de13c1-1d50-4ab9-aa8c-6157781ea12f" />

    (*Image of the full adder I made*)
6. Scaling to a 2-Bit Ripple-Carry Adder

   <img width="989" height="559" alt="image" src="https://github.com/user-attachments/assets/efc0dd6f-a2c6-4d44-bba5-c1440f1ee475" />

    (*Image of the 2-bit ripple adder I made*) 
