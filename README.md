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


**program**
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


Developed by: RegisterNumber:*/


**RTL realization**
<img width="722" height="687" alt="image" src="https://github.com/user-attachments/assets/9750c6c5-04e5-4b79-9cc6-06064181eef0" />

**Output:**
<img width="1920" height="1080" alt="Screenshot (73)" src="https://github.com/user-attachments/assets/0d228ae7-0432-40d2-8281-81e276d063a9" />

**RTL**
<img width="1920" height="1080" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/3e745b9f-3fd5-49db-8d6a-2132d2b3d45b" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

