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
<img width="1644" height="924" alt="Screenshot (80)" src="https://github.com/user-attachments/assets/2f990518-c138-4649-b81a-b81e9e86a761" />
<img width="1920" height="1080" alt="Screenshot (79)" src="https://github.com/user-attachments/assets/72be0fa0-1dd9-453c-9844-d4be679b4c27" />


**RTL**
<img width="1920" height="1080" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/3e745b9f-3fd5-49db-8d6a-2132d2b3d45b" />
<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/8eb0e49f-e37b-4fff-995f-3eb78ebf0152" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

