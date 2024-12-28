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

**Truthtable**

![Screenshot 2024-12-28 213754](https://github.com/user-attachments/assets/2f8014a7-63e1-4417-b3c5-0fbb36f460d9)

 

**Procedure**

Write the detailed procedure here
1.Write a code in quartus software by creating a new project wizard. 2.Run the program to get
output. 3.Then open the RTL viewer and download that image. 4.Pen the new file with University
program VWF. 5.Set end timer and execute, then downloag the waveform.

**Program:**

![Screenshot 2024-12-28 213923](https://github.com/user-attachments/assets/f864619d-6649-4ebb-b545-9d11f53aa27e)

 
 Developed by:MOHANA PRIYA.R
 
 RegisterNumber:24900710


**RTL Schematic**

![Screenshot 2024-12-28 213934](https://github.com/user-attachments/assets/2074b0e9-aa48-491d-9549-4e098ee79e48)


**Output Timing Waveform**

![Screenshot 2024-12-28 213950](https://github.com/user-attachments/assets/3276e814-654e-4b91-885e-1507fbb88079)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



