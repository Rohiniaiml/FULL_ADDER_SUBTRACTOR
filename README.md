## NAME :R ROHINI
## REG NO :24005989
## EXPERIMENT NO 4: FULL_ADDER_SUBTRACTOR




Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

*Full Adder*

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

*Figure -1 FULL ADDER*

*Full Subtractor*

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# TRUTH TABLE

![WhatsApp Image 2024-11-28 at 14 18 30_aa1bb81d](https://github.com/user-attachments/assets/75850a21-97cf-4776-9d50-d8e3838372b7)




# PROCEDURE

Implementing BOOLEAN functions in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.



# PROGRAM:


![WhatsApp Image 2024-11-28 at 14 18 31_c8c4363c](https://github.com/user-attachments/assets/86a3dddf-3294-49ba-a7b3-d8b2abadfd93)




# RTL OUTPUT

![WhatsApp Image 2024-11-28 at 14 18 31_40271efb](https://github.com/user-attachments/assets/fb783286-393a-458f-9d2d-e8fd3a2e9cbd)

# OUTPUT WAVEFORM


![WhatsApp Image 2024-11-28 at 14 18 31_ddaeef8e](https://github.com/user-attachments/assets/e33b6dca-bf74-4481-979b-fae65fc815ec)



# RESULT:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.







