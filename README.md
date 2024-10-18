# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

**half adder**
![WhatsApp Image 2024-10-18 at 13 24 55_8c889d29](https://github.com/user-attachments/assets/957f4078-fcfc-401d-906a-f93ab1b3823a)

** half subtractor**
![WhatsApp Image 2024-10-18 at 13 27 31_1ea83fd4](https://github.com/user-attachments/assets/25f0839f-6f92-439d-a32d-e7c658524d05)



Developed by: NANDHANA.R RegisterNumber:212223040124*/

**RTL Schematic**
** half adder**
![WhatsApp Image 2024-10-18 at 13 25 45_0705e134](https://github.com/user-attachments/assets/49b971e4-bb68-429f-9c6b-db53588954ef)

**half subtractor**
![WhatsApp Image 2024-10-18 at 13 27 52_41e353f8](https://github.com/user-attachments/assets/de77eb3c-5ac6-423c-bd83-c79b39cb7380)



**Output/TIMING Waveform**
**half adder**
![WhatsApp Image 2024-10-18 at 13 26 10_ec975041](https://github.com/user-attachments/assets/a96d6e24-b40e-44bc-8ac5-345c5b58e5e6)

**half subtractor**
![WhatsApp Image 2024-10-18 at 13 28 47_a6bce1d6](https://github.com/user-attachments/assets/cddf10e6-61c0-45c1-9f9c-a5961df73678)



**Result:**
Thus the half adder and half subtractor circuits are designed and the truth tables is verified using quartus software.
