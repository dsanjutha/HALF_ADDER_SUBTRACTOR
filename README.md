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
<img width="1920" height="1080" alt="de_ex_3,ha,program" src="https://github.com/user-attachments/assets/1290ec56-30c3-46a7-8ba0-1f0c6d503c3e" />
<img width="1493" height="847" alt="Screenshot 2025-12-11 223028" src="https://github.com/user-attachments/assets/8f7ed676-d776-41d6-b02c-5f415213c213" />

   
/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: d.sanjutha  RegisterNumber:25015927 */



**RTL Schematic**
<img width="1920" height="1080" alt="de_ex_3,ha,output" src="https://github.com/user-attachments/assets/312589c7-844b-4505-83c3-e467bfddc730" />
<img width="1502" height="853" alt="Screenshot 2025-12-11 222607" src="https://github.com/user-attachments/assets/5e9b8ec5-6f72-4c92-a3b7-0453304548f7" />

**Output/TIMING Waveform**
<img width="1920" height="1080" alt="de_ex_3,ha,wave" src="https://github.com/user-attachments/assets/46f502f3-8a36-43cd-836d-6bc6f0ad2380" />

<img width="1501" height="847" alt="Screenshot 2025-12-11 222935" src="https://github.com/user-attachments/assets/8dc55fd9-1462-413d-a26f-ca36ddc42fd9" />

**Result:**

Thus the given design implement and verifield using truth table
