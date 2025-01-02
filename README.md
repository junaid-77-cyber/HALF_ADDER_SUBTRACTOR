# NAME: JUNAID SARDAR S
# REG NO.24003934
# EXP NO.3 Implementation of Half Adder and Half Subtractor circuit

# AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

# Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

# Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

# Truthtable
1.Truth table for Half Adder

![Screenshot 2024-12-01 113158](https://github.com/user-attachments/assets/406997ab-5d48-4d4e-b956-9c341bf273a4)

2.Truth Table for Half Subtractor

![Screenshot 2024-12-01 113249](https://github.com/user-attachments/assets/6899cb14-392d-4665-bba2-c24a5b440f7d)

# Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# Program:

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

![Screenshot 2024-12-01 130814](https://github.com/user-attachments/assets/ac89ec9d-52dd-46a8-8e8a-8f1678e559ea)

# RTL Schematic Output:

![Screenshot 2024-12-01 130755](https://github.com/user-attachments/assets/757bdc5d-6146-4672-be84-d570c476152b)

# TIMING Waveform

![Screenshot 2024-12-12 111951](https://github.com/user-attachments/assets/861eac28-d4c6-426a-ad51-5cf3e9a15fec)


# Result:
Designed and verified the halfadder and half subtractor circuit and its truth table using verilog programming 
