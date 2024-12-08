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


![Screenshot (60)](https://github.com/user-attachments/assets/11c6708c-01db-4094-8d19-4b3024af492d)


**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Figure -1 FULL SUBTRACTOR**


![Screenshot (61)](https://github.com/user-attachments/assets/276f487a-438e-4dd3-83da-80bfd55b4516)

**Truthtable**

FULL ADDER


![Screenshot (45)](https://github.com/user-attachments/assets/973b5250-c439-499a-896f-dfe424ddf68a)


FULL SUBTRACTOR



![Screenshot (46)](https://github.com/user-attachments/assets/01e37b57-7ac9-453e-bdd1-a175bea67c15)

**Procedure**

Write the detailed procedure here

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram

   
**Program:**

 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

 FULL ADDER

 

![Screenshot (54)](https://github.com/user-attachments/assets/f27b92b6-aa1c-41ce-a80d-27793d044cae)


FULL SUBTRACTOR

![Screenshot (56)](https://github.com/user-attachments/assets/0ea3af91-a560-4d86-aca1-fb9325439111)

developed by:BARKAVI.B
RegisterNumber:24901000


**RTL Schematic**

FULL ADDER


![Screenshot (51)](https://github.com/user-attachments/assets/3696e5cc-3d3c-4e93-81fc-9ce65dc994c6)


FULL SUBTRACTOR


![Screenshot (55)](https://github.com/user-attachments/assets/c8835ca4-7b5f-4e90-9a9f-8a9134422d6c)

**Output Timing Waveform**

FULL ADDER

![Screenshot (53)](https://github.com/user-attachments/assets/69913238-0a4c-491b-bc04-2dea4d719e64)

FULL SUBTRACTOR


![Screenshot (57)](https://github.com/user-attachments/assets/18e00a65-ef85-4fda-9810-8b7c1e3e6417)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



