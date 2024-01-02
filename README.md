# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: YAZHINI S
RegisterNumber:212223050062  
*/

##Code

Half Subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/72dad410-0283-4446-b7c9-d5ebfc95378a)

Full Subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/a5010e5b-f38d-4d05-bf1d-c82f48ac0c86)

Truthtable:

Half subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/cf106abd-ca44-4ba9-a677-6720f1d954a9)

Full subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/cc9be644-6fbc-46cf-ad65-9e2ae5d8baa8)

RTL Viewer:

Half subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/a4f48401-b104-4f9c-9fd7-22cfcec0825b)

Full subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/0f45421d-d45d-449a-9884-ef4b3dc2e49e)

Timing diagram:

Half Subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/5324baf2-96c8-44f1-a6ac-102c5948f7af)

Full subtractor:

![image](https://github.com/yazhini119/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155442058/a96c69d5-be32-4e31-acaa-2d3b5b833af3)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
