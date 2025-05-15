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
module exp_2a (a,b,c,d,f1);
input (a,b,c,d);
output (f1);
assign f1=((~a&b&d)|(a&b&~c)|(~b& ~d));
endmodule
```
```
module exp_2b(w,x,y,z,f2);
input(w,x,y,z);
output f2;
assign f2=((x&y)|(~w&y)|(~y&z));
endmodule
```

Developed by:Mohamed Mustafa Hussain RegisterNumber:*/212224240091

**Output:**

![443755047-3efa9bd8-ab46-4913-be7b-06697f69d29e](https://github.com/user-attachments/assets/3b7a9f89-096a-46a1-90ca-2cfcfbbb033a)


![443754351-9b73d0bb-5ff9-4924-a33b-7ee4e216bf7d](https://github.com/user-attachments/assets/bd2ca833-0173-4171-bc7c-6595254cb2ce)


**Timing Diagram**

![443755339-faeec3b4-0a49-4c7f-a2f2-2dc1d357e73d](https://github.com/user-attachments/assets/73ed2253-1baf-4a41-8d54-f5600c701429)



![443755826-5d3ca894-b2c3-4629-8138-5da88885128f](https://github.com/user-attachments/assets/bb836eb7-0d3e-4f77-923f-1e6307f5d818)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

