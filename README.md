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

HALF SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/f504dd5c-58fc-4eed-bb0b-50760f841184)
FULL SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/fde0a99d-0df4-4490-b989-3d5d23c4787b)

/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: S LALIT CHANDRAN
RegisterNumber: 23004048
*/

## Output:

## Truthtable

HALF SUBTRACTER

![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/03ff040b-d95c-4dcc-b91c-c21f185fe423)

FULL SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/bbdd0117-d97a-495d-95ab-3ccaf0923c2a)


##  RTL realization

HALF SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/4743e039-586d-42cc-ac69-fa8890ca7187)

FULL SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/786a82e5-294f-43fe-9420-f94c9672db70)


## Timing diagram 

HALF SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/5e1589a4-c17b-48eb-ad53-b37befd62053)

FULL SUBTRACTER
![image](https://github.com/lalitchandran/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/137707725/ae8ff2dd-6896-41ce-9a09-3aaa63472894)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
