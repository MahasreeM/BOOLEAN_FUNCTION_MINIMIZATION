# BOOLEAN_FUNCTION_MINIMIZATION
# Developed by:MAHA SHREE M
# RegisterNumber:*212224110035
# Date:12.03.2025

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
```
 module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

 module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule
```

**RTL realization**

**Output:**

**RTL**
![Screenshot (170)](https://github.com/user-attachments/assets/f288e5b9-3a53-46fc-8b4a-5256861c4306)

![Screenshot (172)](https://github.com/user-attachments/assets/b8d94211-7547-4199-91a2-f55db680b6f0)

**Timing Diagram**
![Screenshot (171)](https://github.com/user-attachments/assets/f157247a-71fa-42dd-94ac-76ddd7dc3607)

![Screenshot (173)](https://github.com/user-attachments/assets/b12f3799-8bde-451b-9962-bf843aae9002)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

