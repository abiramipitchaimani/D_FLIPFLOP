# D_FLIPFLOP

# Aim
To simulate and synthesis of D_flipflop using vivado 2023.2
# Software required
Vivado 2023.2
# Procedure
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button.

Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)
# Program
```
Developed by: P.Abirami
Register number: 212222060006
```
```
module dff(d,clk,rst,Q);
input d,clk,rst;
output reg Q;
always @(posedge clk)
begin
if(rst==1)
Q=1'b0;
else
Q=d;
end
endmodule
```
# Output
![image](https://github.com/abiramipitchaimani/D_FLIPFLOP/assets/163704307/305160e2-1562-4094-988e-c5ff442ef53e)


# Result
Thus the simulation and synthesis of D_flipflop using vivado 2023.2 is successfully executed and verified.

