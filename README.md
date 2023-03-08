# Ngspice-Verilog-AMS
Simulation with Ngspice and Verilog-AMS

Step 1: Convert Verilog-AMS to .osdi file

.\openvaf.exe .\psp103.va

Step 2: Run spice netlist using Ngspice 

C:\ngspice-39_64\Spice64\bin\ngspice .\psp_inverter.sp
