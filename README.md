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

Developed by:Dinesh.S

RegisterNumber:212222230033

```
library IEEE;
use IEEE.STD_LOGIC_1164.ALL;

entity booleanexp is 
    Port ( INO1 : in STD_LOGIC;    --- OR gate input
	        INO2 : in STD_LOGIC;    --- OR gate input
			  OO  : out STD_LOGIC);   --- OR gate output
end booleanexp;

architecture Behavioral of booleanexp is 
begin
OO <= INO1 or INO2;   --- 2 input OR gate
end Behavioral;
```
![Screenshot 2024-03-20 125311](https://github.com/ajinajoshpin/BOOLEAN_FUNCTION_MINIMIZATION/assets/148514578/9aaa43c1-6dea-4ada-964a-6932a40dc881)

**RTL realization**
![Screenshot 2024-03-20 130933](https://github.com/ajinajoshpin/BOOLEAN_FUNCTION_MINIMIZATION/assets/148514578/70420e12-71c5-4c16-9e5b-68107063fdaa)

**Output:**
![Screenshot 2024-03-20 125925](https://github.com/ajinajoshpin/BOOLEAN_FUNCTION_MINIMIZATION/assets/148514578/98edadfb-3ce6-4e31-96ce-5e286703df41)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

