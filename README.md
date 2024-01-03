# NAME:KARTHICK KISHORE.T
# REF NO:212223220047
# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure:
Create a New Project: Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).
Create a New Design File: Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).
Write the Combinational Logic Code: README.md *Open the newly created Verilog or VHDL file and write the code for your combinational logic. 4.Compile the Project: *To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device. 5.Analyze and Fix Errors: *If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window. *Review and fix any issues in your code if necessary. *View the RTL diagram. 6.Verification: *Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF". *Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All. Program: *Give the Input Combinations according to the Truth Table and then simulate the Output Waveform.



## Program:
![286264938-c2ed5ab6-70f5-415e-8840-a7d62660bcae](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/149347526/8cc5f5ea-bf42-49f2-818a-6cab28097590)

## RTL realization:

![286265174-9defe58e-3984-4fd8-90d5-70dbd2504888](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/149347526/c83f5d40-b247-4a57-8c82-2b182fef45a3)

# TRUTH TABLE:

![286265619-09af1344-a15e-4442-87d1-a6178e78d7f4](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/149347526/f31d6a12-2214-441e-9c86-315fb1163233)


# TIMING DIAGRAM:
![286265233-bb9e1b09-69d2-4f78-897b-c858dc59ac3a](https://github.com/vasanthkumarch/Experiment--02-Implementation-of-combinational-logic-/assets/149347526/f119f415-72b3-4e67-b560-014d11781a6b)



## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
