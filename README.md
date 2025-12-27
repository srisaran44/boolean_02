AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

F2=xy’z+x’y’z+w’xy+wx’y+wxy

Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Theory

Logic Diagram

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

Program: F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
Developed by:J SRI SARAN RegisterNumber:25015592

RTL realization
OUTPUT;
<img width="1038" height="518" alt="Screenshot 2025-12-27 131733" src="https://github.com/user-attachments/assets/21020e6e-4ad4-4890-8789-30ce47e4596e" />
<img width="1038" height="565" alt="Screenshot 2025-12-27 131744" src="https://github.com/user-attachments/assets/cf08727d-5dde-4194-8ba9-62b06cbe52b2" />

RESULT;
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

