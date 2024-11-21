# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-21 at 6 44 45 PM](https://github.com/user-attachments/assets/11594037-dfa4-46d4-b5d0-018cc8d16d70)


Area report:
![WhatsApp Image 2024-11-21 at 6 44 44 PM](https://github.com/user-attachments/assets/0cca0e23-ae7a-4aab-b209-d6d75bd1f9fc)


Power Report:
![WhatsApp Image 2024-11-21 at 6 44 45 PM (1)](https://github.com/user-attachments/assets/73df11cc-6c39-4a9f-a261-ff33b7d8d6f8)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
