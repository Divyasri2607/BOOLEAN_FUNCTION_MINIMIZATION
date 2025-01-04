# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions.

Truth Table:

![Screenshot 2024-12-23 091110](https://github.com/user-attachments/assets/4cc2f127-6d38-46dc-ba26-956f0a2c90a9)

F1:

![WhatsApp Image 2024-12-21 at 08 56 17_d6f94470](https://github.com/user-attachments/assets/ca675f4f-1205-4177-9731-db1c5a9a2ae0)

F2:

![WhatsApp Image 2024-12-21 at 08 56 30_df79a404](https://github.com/user-attachments/assets/305af116-706e-451e-9982-73c87cb706c5)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: divya sri 
RegisterNumber: 24901155

F1:

```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
F2:

```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL**

F1:

![Screenshot 2025-01-04 110157](https://github.com/user-attachments/assets/6e7c1b2b-b128-401a-b794-16d3374f96d6)


F2:

![Screenshot 2025-01-04 110339](https://github.com/user-attachments/assets/6bf0b3c5-bc5c-4bc3-b2bc-c85ed062ed82)


**Timing Diagram**

F1:

![Screenshot 2025-01-04 110517](https://github.com/user-attachments/assets/439613b3-23dd-4890-b8f9-61f3bef3af95)


F2:

![Screenshot 2025-01-04 110637](https://github.com/user-attachments/assets/f2564b54-341a-40f4-a52c-99d251990b58)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

