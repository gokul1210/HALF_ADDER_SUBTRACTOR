## NAME : GOKUL S
## REG NO :212224230075

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

Figure -01 HALF ADDER

 ![HALF SUB](https://github.com/user-attachments/assets/73a20d59-85e2-47d9-9974-2cec19de4251)



**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

![Screenshot 2025-04-15 112110 - Copy](https://github.com/user-attachments/assets/5118116e-5c4e-4e21-80fa-8f0e80896353)



Figure -02 HALF Subtractor

**Truthtable**
HALF ADDER

![Screenshot 2025-04-16 084057](https://github.com/user-attachments/assets/ac8aa90c-08f3-4509-9250-2d94fa45e98c)

HALF SUBTRACTOR

![Screenshot 2025-04-16 083851](https://github.com/user-attachments/assets/89169a3b-8bf0-450a-8fe7-d5c37a978895)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

HALF ADDER 

![HALF ADDER](https://github.com/user-attachments/assets/af1015aa-9768-4e8f-a8f2-040ea6a107ff)


HALF SUBTRACTOR 


![HALF SUB 2](https://github.com/user-attachments/assets/b71394e0-1680-40ce-8112-f67254c71d30)


**RTL Schematic**


HALF ADDER :
![Screenshot 2025-04-15 112258 - Copy](https://github.com/user-attachments/assets/41dc41e0-fee2-4907-a9a1-6f0fc3a7660d)



**Output/TIMING Waveform**

![HALF SUB 1](https://github.com/user-attachments/assets/417e7abc-7a9a-4d73-b65c-bdeaf70ffd45)


**Result:**

THE OUTPUT IS EXECUTED SUCCESSFULLY
