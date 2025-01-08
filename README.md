# FULL_ADDER_SUBTRACTOR

NAME : B.BARKAVI

REFERENCE NO : 24901000

**EXPERIMENT NO : 4 IMPLEMENTATION OF FULL ADDER AND FULL SUBTRACTOR**


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

 

![Screenshot (139)](https://github.com/user-attachments/assets/ced0cc9d-f2bd-4534-a85c-847075097df5)


FULL SUBTRACTOR


![Screenshot (142)](https://github.com/user-attachments/assets/9b38b4d8-a120-4352-a446-518b999095b2)


**RTL Schematic**

FULL ADDER


![Screenshot (140)](https://github.com/user-attachments/assets/83edf60f-a15b-4842-9395-53ddbbf03c0b)


FULL SUBTRACTOR


![Screenshot (143)](https://github.com/user-attachments/assets/a24fd3a9-2bcf-4f54-9d71-5cc9062b1a7b)


**Output Timing Waveform**

FULL ADDER


![Screenshot (141)](https://github.com/user-attachments/assets/29a72306-134b-4139-ad13-fb2205b6ae21)

FULL SUBTRACTOR


![Screenshot (144)](https://github.com/user-attachments/assets/da23ece0-fb9a-45fa-bb04-179577049804)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



