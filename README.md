# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![DE WRITTEN ](https://github.com/user-attachments/assets/1e0f39c5-6e4a-4670-88f0-5607d8d0e540)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by: DEVA ABISHEK P
RegisterNumber:212223110008
```
```
**EXP 2A
~~~
module EXP2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
~~~
**EXP 2B
~~~
module EXP2B(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&z)|(x&y)|(w&y&~z));
endmodule
~~~
```
**RTL realization**
EXP 2A
![Screenshot 2025-03-14 142551](https://github.com/user-attachments/assets/b1d1b319-6438-4305-b914-63dafe7f3c1a)
EXP 2B
![Screenshot 2025-03-14 205648](https://github.com/user-attachments/assets/edaaa47b-3a3e-465b-b9f3-b70935a75357)

**Timing Diagram**
EXP 2A
![Screenshot 2025-03-14 143945](https://github.com/user-attachments/assets/30e1b496-6674-491d-ad62-409390ddec5a)
EXP 2B
![Screenshot 2025-03-14 205908](https://github.com/user-attachments/assets/f6d462f8-c65b-428b-8f99-f42b5777307d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

