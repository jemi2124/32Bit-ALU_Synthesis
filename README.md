# Exp-5: 32Bit-ALU_Synthesis

## Aim :

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

* The Available technology nodes are 180nm ,90nm and 45nm.

* In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

* The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

* Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![Screenshot (53)](https://github.com/user-attachments/assets/895d4386-60d7-4c16-9cb1-da84a523b2bd)

#### Area report:

![Screenshot (55)](https://github.com/user-attachments/assets/fc16d646-b9de-485d-82bb-e88c15a4cb96)

#### Power Report:

![Screenshot (54)](https://github.com/user-attachments/assets/4ee28854-c5f3-443c-a326-5d233172ceb8)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
