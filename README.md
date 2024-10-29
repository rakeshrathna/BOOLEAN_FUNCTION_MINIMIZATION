# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![WhatsApp Image 2024-10-29 at 14 17 16_7cedf2b9](https://github.com/user-attachments/assets/ef60475b-3ba0-40a5-82dc-0e03fac47eaa)


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
module exp22(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

```

Developed by:RAKESH RATHNA
RegisterNumber:24900592


**RTL realization**

![exp22](https://github.com/user-attachments/assets/e4ec2409-6fb9-4d0e-a5d3-1840d186e223)






**Timing Diagram**

![Screenshot 2024-10-23 094243](https://github.com/user-attachments/assets/1cf0f8ea-6a8c-4186-a524-9c3d2bba4c57)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

