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

![WhatsApp Image 2024-11-18 at 23 41 49_8ef9d8d5](https://github.com/user-attachments/assets/7b32f36f-843b-4619-861c-2a81be7cd3ef)


#### Area report:

![Screenshot (313)](https://github.com/user-attachments/assets/3abd814f-b47c-4325-a657-8ebd057612fd)


#### Power Report:

![Screenshot (317)](https://github.com/user-attachments/assets/0f1e3419-f3b3-4b87-b11d-89bdf3c5ab50)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
