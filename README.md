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

Full Adder

![Screenshot 2025-04-22 103249](https://github.com/user-attachments/assets/a74375bd-22b8-401a-abf7-d7cf4e7c63a3)

Full Subtractor

![Screenshot 2025-04-22 103301](https://github.com/user-attachments/assets/3660fb62-9538-4cfc-b18d-550b045fd9e2)


**Procedure**

Full Adder:
1.Open Quartus II and create a new project.
2.Use schematic design entry to draw the full adder circuit. 
3.The circuit consists of XOR, AND, and OR gates. 
4.Compile the design, verify its functionality through simulation. 
5.Implement the design on the target device and program it.

Full Subtractor:
1.Follow the same steps as for the full adder. 
2.Draw the full subtractor circuit using schematic design. 
3.The circuit includes XOR, AND, OR gates to perform subtraction. 
4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program:**

Full Adder

![Screenshot 2025-04-16 083306](https://github.com/user-attachments/assets/72f6c530-2682-4ef2-96ab-dcb520c98e49)

Full Subtractor

![Screenshot 2025-04-16 084259](https://github.com/user-attachments/assets/5b99f512-2f58-48ce-b939-2de8a0972227)


**RTL Schematic**

Full Adder

![Screenshot 2025-04-16 083317](https://github.com/user-attachments/assets/92f8ac45-0489-4f46-b1b9-a82ba35eeeb4)

Full Subtractor

![Screenshot 2025-04-16 084248](https://github.com/user-attachments/assets/da167a48-ba68-4771-8d26-067e321d3038)


**Output Timing Waveform**

Full Adder

![Screenshot 2025-04-16 083605](https://github.com/user-attachments/assets/e5c9fc8a-d1ab-4f92-84cc-b98d383ae963)

Full Subtractor

![Screenshot 2025-04-16 084440](https://github.com/user-attachments/assets/68683826-e509-4b60-9a40-9e583d8cf314)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



