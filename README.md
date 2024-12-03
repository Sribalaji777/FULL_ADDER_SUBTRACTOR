![image](https://github.com/user-attachments/assets/887a271f-70f6-43a1-9da0-b15d73ed72bb)# FULL_ADDER_SUBTRACTOR

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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:SRIBALAJI S RegisterNumber:24900249
*/
![Screenshot 2024-12-03 085156](https://github.com/user-attachments/assets/dcc33210-0dee-4acd-80ef-76a3a5557223)


![Screenshot 2024-12-03 090843](https://github.com/user-attachments/assets/77b612a4-94ff-41d8-abf3-3a086d235544)


**RTL Schematic**
![Screenshot 2024-12-03 085127](https://github.com/user-attachments/assets/ec0bd1f0-7500-462a-aa09-5e1ff5179fc5)


![Screenshot 2024-12-03 091047](https://github.com/user-attachments/assets/047253ed-926f-4dec-9edc-3afdee2ab71b)


**Output Timing Waveform**
![Screenshot 2024-12-03 085625](https://github.com/user-attachments/assets/980d6664-dad6-4b54-85d8-b919ed588a07)


![Screenshot 2024-12-03 091124](https://github.com/user-attachments/assets/1c007847-3261-486a-901a-6006fdd78c5b)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



