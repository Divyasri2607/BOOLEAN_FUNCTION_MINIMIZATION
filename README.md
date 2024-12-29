# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
```
Developed by: Divya sri V
RegisterNumber:24901155
```
*/


**RTL realization**
![Screenshot 2024-12-29 165038](https://github.com/user-attachments/assets/10194d76-4021-41ea-b7ea-7ffd9382692b)

**Output:**
![Screenshot 2024-12-29 165052](https://github.com/user-attachments/assets/cc3f5823-426a-4bf7-ac9b-70b1d0b95d6b)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

