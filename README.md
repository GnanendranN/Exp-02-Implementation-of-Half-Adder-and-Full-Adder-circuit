# Exp 03 Implementation of Half Adder and Full Adder circuit
## Name: GNANENDRAN N
## REGISTER NUMBER : 23006661
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
### Program:
#### Half Adder
![halfadder](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/6a73250b-30a4-4ad1-8bc1-61b274890822)
#### Full Adder
![fulladder](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/0e67cf5c-d102-418b-a45b-24b6b2016cdb)

### TRUTH TABLE 
#### Half adder Circuit:
![287159471-84fe2dfb-ab2e-46b9-8689-e416047c8fc8](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/e187bb77-5963-4062-8b73-eccfa06a4acb)

#### Full adder Circuit:
![287159508-69eb05f1-2112-4a3a-96a2-128846fc4446](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/d2a7988c-3ff4-43d5-aaaa-9f861df9693a)

### RTL
#### Half adder Circuit:
![287159573-b62d0b89-2ae1-4c66-a0db-b1f03ea0e16b](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/883847b1-bb3f-4a6b-97de-384324be9312)

#### Full adder Circuit:
![287159639-b0ff4b9c-d7dc-4229-82df-d2866f9cc31e](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/a68fc366-b458-43f9-841b-3ef9748b4262)

### Output:
#### Half adder Circuit:
![287159809-ab9575e1-695c-46e7-bc3b-ed2440e7d734](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/3f5233ea-61fb-4bf6-a0eb-5beba725ab6f)

#### Full adder Circuit:
![287159853-6d94b0e2-bcd1-4d5f-a882-3a83f519bb8b](https://github.com/GnanendranN/Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138955207/3d36c38b-6ee8-4da5-ab7b-cca87b53ee0c)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
