![Screenshot 2023-12-26 231420](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/91efa243-7646-401d-a6d4-87b637a98c4a)# Experiment--03-Half-Subtractor-and-Full-subtractor
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

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Aravindan D
RegisterNumber: 23013092

## CODE :
![Screenshot 2023-12-26 230902](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/83d99d73-6c28-4b24-892e-5f57e1e6eb81)
![Screenshot 2023-12-26 230925](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/f13aadaf-3ba5-491d-bd91-b3477d381bdd)


## Truthtable
![image](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/d1e760d0-d4ff-4c97-b71f-37ffbc57de5e)
![Screenshot 2023-12-26 231031](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/7ea4e8ad-ca10-4b6a-9abf-49b625388bb7)


##  RTL Diagram 
![Screenshot 2023-12-26 231119](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/748b95a9-f5dd-4a94-a769-9ac67ecbca4a)

![Screenshot 2023-12-26 231200](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/fa010e3d-fc48-4823-9e3d-4152b02a495e)


## Timing diagram 
![Screenshot 2023-12-26 231420](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/e802a6b2-7c8e-497b-ade6-0c116b486b38)

![Screenshot 2023-12-26 231602](https://github.com/Aravindan2006/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/151760062/4f79368d-6b83-4f47-9719-7a2e12afdc64)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
