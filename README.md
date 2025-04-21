# FULL_ADDER_SUBTRACTOR
name : imthiyas ahamed.m
reg no:212224901087
I st year EEE

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
![WhatsApp Image 2025-04-16 at 09 28 30_2cb057d2](https://github.com/user-attachments/assets/b56f84f7-6673-49d3-9795-a6c38b5d52cb)
![WhatsApp Image 2025-04-16 at 09 28 30_b80c876f](https://github.com/user-attachments/assets/d73b1fe7-2415-4092-99da-ee82441ad9b3)


**Procedure**
![Screenshot 2025-04-16 085653](https://github.com/user-attachments/assets/3167518b-40ce-47af-931a-06463c75c405)
![Screenshot 2025-04-15 104524](https://github.com/user-attachments/assets/ace78e1f-3bfb-481c-a959-9fc56abe2d48)



**Program:**


**RTL Schematic**
![Screenshot 2025-04-15 104428](https://github.com/user-attachments/assets/f5e81d04-c458-4b47-ad25-9e3768104fd0)
![Screenshot 2025-04-16 085635](https://github.com/user-attachments/assets/2d5f6d3b-7c9f-439e-9424-118ef39b7713)
****

**Output Timing Waveform**
![Screenshot 2025-04-15 111145](https://github.com/user-attachments/assets/bb2eaac6-6316-4f09-8ce7-d948ee4ab94b)
![Screenshot 2025-04-16 091642](https://github.com/user-attachments/assets/151ffcdc-3b7c-436a-b56a-4115eea79c23)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



