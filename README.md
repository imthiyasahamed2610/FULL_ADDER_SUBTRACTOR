# FULL_ADDER_SUBTRACTOR

Name :imthiyas ahamed
Reg no :212224050012
Ist yeas EEEE

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

![WhatsApp Image 2025-04-16 at 09 28 30_2cb057d2](https://github.com/user-attachments/assets/af34b539-2a67-4a79-98b9-781dd8035074)

![WhatsApp Image 2025-04-16 at 09 28 30_b80c876f](https://github.com/user-attachments/assets/e7e1f811-9dc2-4383-bdee-7da51a21e380)

**Procedure**



**Program:**


![Screenshot 2025-04-15 104428](https://github.com/user-attachments/assets/c8e66928-c52e-4944-9a48-19c850a03531)

![Screenshot 2025-04-16 085635](https://github.com/user-attachments/assets/7f6a29fe-f153-4121-be44-9d35581b3eb1)


**RTL Schematic**

![Screenshot 2025-04-15 104524](https://github.com/user-attachments/assets/4eb40e2f-970e-44ea-918b-9be769bb2608)


**Output Timing Waveform**

![Screenshot 2025-04-15 111145](https://github.com/user-attachments/assets/ae4818d1-d6a8-4cdb-8f54-dbe9165a0604)

![Screenshot 2025-04-16 091624](https://github.com/user-attachments/assets/bdad4550-1cc6-44f4-8235-bba1c0742313)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



