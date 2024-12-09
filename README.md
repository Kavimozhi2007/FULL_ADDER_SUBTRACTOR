
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
![WhatsApp Image 2024-12-09 at 9 09 54 PM](https://github.com/user-attachments/assets/eecd4c81-82b7-43d4-93b0-6f651bb9b61a)
![WhatsApp Image 2024-12-09 at 9 09 58 PM](https://github.com/user-attachments/assets/37ab131c-ea4a-48e2-b6ff-ca764a5b1ea1)


**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
full adder
![full addre](https://github.com/user-attachments/assets/3f783c54-3a8b-4ab5-b587-67b0f14c77ff)
full subractor
![full subractor](https://github.com/user-attachments/assets/d3b6a9da-03e1-4324-b89b-71406e8b8185)


**Output Timing Waveform**
full adder

![full adder](https://github.com/user-attachments/assets/ada231bc-0572-4a87-8635-28f781874c03)

full subractor

![full subractor waveform](https://github.com/user-attachments/assets/869ba30f-5cd9-4a6d-bf4c-cfee964d5bcc)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



