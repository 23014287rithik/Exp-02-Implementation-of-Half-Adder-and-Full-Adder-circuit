# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
### Half Adder

 ![Screenshot 2023-12-26 173456](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/6a9f26eb-d186-4237-8602-d649fbdd79ef)

### Full Adder

![Screenshot 2023-12-26 173501](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/fc36574d-462e-4b3a-81bf-2ede359b8361)

 

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Rithik-V
RegisterNumber:  23014287
*/
Logic symbol & Truthtable
RTL realization
### Half Adder

![Screenshot 2023-12-26 173505](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/dbf3e66b-8199-412a-98c7-5ed5ee71778f)


### Full  Adder

![Screenshot 2023-12-26 173512](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/ea995fd9-6243-4c13-8a43-b84d03ae8681)


### Output:
### Truth table

### Half  Adder
![Screenshot 2023-12-26 173518](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/276d71bb-a104-40a8-9aad-71cc99dab248)


### Full  Adder

![Screenshot 2023-12-26 173524](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/713f01ba-ca75-41b5-ae18-88d544a40e04)

### TIMING DIAGRAM
### Half   Adder
![Screenshot 2023-12-26 173533](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/fb62a6a4-1112-4d95-afdb-73d2a0ab7d83)

 ### Full  Adder

![Screenshot 2023-12-26 173543](https://github.com/23014287rithik/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150985832/1acd7177-993f-41aa-8ce4-8883c5884514)

 
### Result:
Thus a Half Adder and Full Adder is designed and its truthtables are verified in Quartus using
Verilog programming
