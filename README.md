# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin


**Procedure**

Open Quartus Prime Software

Create a New Project

Create Verilog HDL File

Compile the Project

Open Simulation Tool

Run the Simulation and view results in the waveform viewer or console

Verify Truth Table

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
exp 4a:

![program](https://github.com/user-attachments/assets/e0debc4c-a0d2-4319-824d-b6a87931fa2e)

exp 4b:

![program](https://github.com/user-attachments/assets/a9eca8c2-6b35-44b2-967f-1a2d74d8503f)



**RTL Schematic**

exp 4a:

![circuit](https://github.com/user-attachments/assets/3c8e210a-cc11-40f1-ae95-5fb22e493041)

exp 4b

![circuit](https://github.com/user-attachments/assets/9e01900a-1e16-4d12-b3ee-fd4a07e5c81c)


**Output Timing Waveform**

exp 4a:

![waveform](https://github.com/user-attachments/assets/318827b4-5059-4a4b-8c5b-acc0dcb89c18)

exp 4b:

![waveform](https://github.com/user-attachments/assets/901b1df3-e77f-43e1-b735-7ddacc6c3bf3)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



