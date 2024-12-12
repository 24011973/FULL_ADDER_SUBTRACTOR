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

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![WhatsApp Image 2024-12-12 at 22 23 20_1bf82512](https://github.com/user-attachments/assets/3eda418d-8af4-48fe-9adb-60e6392413ad)
![WhatsApp Image 2024-12-12 at 22 23 21_2124a516](https://github.com/user-attachments/assets/a93dc141-bc56-4431-9cd2-3537384df0bf)

**Output Timing Waveform**
![WhatsApp Image 2024-12-12 at 22 23 22_2a7c171d](https://github.com/user-attachments/assets/754cf410-50ae-4b1b-97d0-c4d14b97d60b)
![WhatsApp Image 2024-12-12 at 22 23 23_a49c5876](https://github.com/user-attachments/assets/7ca7584d-2400-4e2b-98df-9c25026a581b)

**Result:**
A Full Adder and a Full Subtractor are advanced digital circuits that perform addition and subtraction on binary numbers, considering not only the current input bits but also the carry and borrow from previous operations.
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



