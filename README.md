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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
![FULL ADDER 1](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/6b33e9b0-c789-4523-9ab3-767b8f0f54c7)
![PRO 2](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/7883b3ac-e374-4947-980a-9dbba975c84a)
### RTL
![FULL ADDER 1](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/80bf3c38-5221-4f65-a7fb-b430b90e2a42)
![HALF ADDER](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/a7163f0b-365d-4160-8d93-4ac87b263ef6)
### TIMING DIAGRAM
![FULL ADDER TIMMIG DIAGRAM](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/aaac25ad-bef4-4bae-aa52-5cb48b9555db)
![HALF ADDER TIMMING](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/ab1e3127-85c7-4c6f-a41e-b7e4ac231369)
### TRUTH TABLE 
![FULL ADDER TT](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/f5f71525-a4ae-4932-8ad7-469be7144f5e)
![HALF ADDER TT](https://github.com/Sharonsteffani2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979934/5c6e53e2-13b7-495a-8b8d-780f467d8b19)
### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
