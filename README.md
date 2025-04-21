# FULL_ADDER_SUBTRACTOR

name : imthiyas ahamed
Reg no : 212224050012
Ist year EEE

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

**Truthtable**

![WhatsApp Image 2025-04-16 at 09 28 30_2cb057d2](https://github.com/user-attachments/assets/6338c4a8-925a-4f62-9edb-c756837d389e)

![WhatsApp Image 2025-04-16 at 09 28 30_b80c876f](https://github.com/user-attachments/assets/4b5f0f7b-85cf-4f88-9f69-0a3eb87cbff9)

**Procedure**

Write the detailed procedure here

**Program:**


![Screenshot 2025-04-15 104428](https://github.com/user-attachments/assets/ddbf06e1-eee0-488a-a464-bb1cc7204f16)

![Screenshot 2025-04-16 085635](https://github.com/user-attachments/assets/d3343892-1f8b-482f-a495-0b9d62ac2d21)


**RTL Schematic**

![Screenshot 2025-04-15 104524](https://github.com/user-attachments/assets/c9485fde-50c2-44c2-a92f-66ab26998994)

![Screenshot 2025-04-16 085653](https://github.com/user-attachments/assets/6227e074-892b-48b3-a18e-f422cf83058f)

**Output Timing Waveform**
![Screenshot 2025-04-15 111145](https://github.com/user-attachments/assets/cfd61cb4-9970-4810-86a0-ffd027d96550)

![Screenshot 2025-04-16 091642](https://github.com/user-attachments/assets/9046136e-bde2-4953-985d-bd5973c9f9ad)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.





