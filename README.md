# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot 2025-05-26 152422](https://github.com/user-attachments/assets/4ddd7d93-a2ec-43e4-9328-5e155e4bac10)


#### Area report:

![Screenshot 2025-05-26 152820](https://github.com/user-attachments/assets/a874e1cb-56a9-4207-8824-b1df025d7cbf)

#### Power Report:

![Screenshot 2025-05-26 152717](https://github.com/user-attachments/assets/4ab38059-0499-4019-a07b-5439a6352964)

Gates report :

![Screenshot 2025-05-26 152748](https://github.com/user-attachments/assets/3ec8ea18-02c6-43ab-8b1b-d4d2f09b50e4)

Timing report:


![Screenshot 2025-05-26 152656](https://github.com/user-attachments/assets/8ad830cd-ab8f-4981-b2de-4d3544f2785c)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
