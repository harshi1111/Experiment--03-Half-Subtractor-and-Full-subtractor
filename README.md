## PROJECT BY: HARSHITHA.V                                             
## REG-NO:23002305
# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
## Theory:
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor:
## Half Subtractor:
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor:
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)
Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure:
 Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.
 
## Program:
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. */

## Truthtable:
## Half Subtractor:
![Screenshot (15)](https://github.com/harshi1111/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/84671735/1be9b039-6264-4862-af48-8cbb0b84d1b6)
## Full Subtractor:
![Screenshot (17)](https://github.com/harshi1111/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/84671735/4d9ea9ef-ecca-4af8-bf2d-ae0eabef5d72)

##  RTL realization
## Half Subtractor:
![Screenshot (11)](https://github.com/harshi1111/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/84671735/91d47775-9b2c-423a-93be-7bf6df1a938f)

## Full Subtractor:
(![Screenshot (13)](https://github.com/harshi1111/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/84671735/d31394e0-5852-42c4-88bf-b829a2195732)
)

## Timing diagram:
## Half Subtractor:
(![Screenshot (7)](https://github.com/harshi1111/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/84671735/fbb22acc-75b3-4cee-b7f2-209804cfecec)
)
## Full Subtractor:
![Screenshot (9)](https://github.com/harshi1111/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/84671735/73917a72-f380-499c-988b-fe2061c88f66)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
