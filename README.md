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
```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: Vishnu Rathan B
RegisterNumber: 24001855
 ```
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
**RTL realization**

![Screenshot 2024-12-05 191624](https://github.com/user-attachments/assets/a4c51298-0bf4-4c34-bac9-b6fe67091536)

**Output:**

![Screenshot 2024-12-05 191645](https://github.com/user-attachments/assets/1b088c1b-b9a1-4433-999c-4e9a7e7b8d7d)

**Timing Diagram**

![Screenshot 2024-12-05 191701](https://github.com/user-attachments/assets/91580e94-f7bd-4f2a-a8ac-7a2e1755ba49)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

