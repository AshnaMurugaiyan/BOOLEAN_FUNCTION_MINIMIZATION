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

Developed by: ASHNA M
RegisterNumber:* 212225040032
```
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```


**RTL realization**

**Output:**
<img width="1918" height="983" alt="Screenshot 2026-05-21 141958" src="https://github.com/user-attachments/assets/49d40b9e-9659-4e28-b926-0bf3e1715875" />

**RTL**
<img width="1600" height="900" alt="351fab58-f8f5-485b-a9cd-ad2025d03b32" src="https://github.com/user-attachments/assets/d82f6641-3716-4270-b818-1b373e7082fc" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

