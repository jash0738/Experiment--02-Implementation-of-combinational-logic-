# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
## NAME: M.R.JASHWANTH
## REGISTERNUMBER : 23005691
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 


## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
module combinationalcircuit(f1,a,b,c,d);

input a,b,c,d;

output f1;

wire abar,bbar,cbar,dbar,x1,x2,x3,x4,x5;

assign abar=~a;

assign bbar=~b;

assign cbar=~c;

assign dbar=~d;

assign x1=abar&bbar&cbar&dbar;

assign x2=a&cbar&dbar;

assign x3=bbar&c&dbar;

assign x4=abar&b&c&d;

assign x5=b&cbar&d;

assign f1=x1|x2|x3|x4|x5;

endmodule 
*/
## TIMING DIAGRAM
![image](https://github.com/jash0738/Experiment--02-Implementation-of-combinational-logic-/assets/139841600/89f57763-fa02-4b92-90fe-0f4dfe17fbbb)
## TRUTH TABLE
![image](https://github.com/jash0738/Experiment--02-Implementation-of-combinational-logic-/assets/139841600/fffb637e-34c7-48b2-bba4-46bba53fe916)
## RTL realization
![image](https://github.com/jash0738/Experiment--02-Implementation-of-combinational-logic-/assets/139841600/5f51d0ea-03fd-43cc-b971-dfeaa0dd6b32)
## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
