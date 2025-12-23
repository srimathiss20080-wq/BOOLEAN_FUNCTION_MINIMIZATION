# BOOLEAN_FUNCTION_MINIMIZATION
***Date:04/12/2025**


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
Boolean Function
------------------------------------------------
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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

**Developed by** Srimathi S
**RegisterNumber** 25017525


<img width="937" height="579" alt="Screenshot 2025-12-04 152550" src="https://github.com/user-attachments/assets/3ab6261a-012a-4328-a6fe-cdc1b89f5fd9" />




**RTL**
**RTL realization**


<img width="937" height="579" alt="Screenshot 2025-12-04 152550" src="https://github.com/user-attachments/assets/3ab6261a-012a-4328-a6fe-cdc1b89f5fd9" />


**Timing Diagram**

<img width="1258" height="633" alt="Screenshot 2025-12-04 152606" src="https://github.com/user-attachments/assets/75a9e402-8446-450d-a3b1-0fb3f5b4390c" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

