# Verilog_sorting
Implementation of bubble sort using recursion technique in verilog.
This project was implemented and tested in Xilinx ISE version 14.7 (webpack edition). 

These Verilog HDL files simulates a circuit that imports 4 numbers, sort them in ascending order (bubble sort is used) 
and display the sorted numbers in the simulation window. The numbers were imported whenever the signal named partC goes high. 
The signal partA decides which number (1st, 2nd, 3rd, 4th) to be imported and the signal partB decides what values to be imported (10, 5, 14, 6) in this project. 
Once all the values have been imported, the sorting algorithm starts to sort the values and arrange them in ascending order when the signal named partD goes high 
(at the positive edge of the signal partD). When the sorting is completed, the start_display bit will be set to 1. 
Always at the positive edge of the signal named display, and when the start_display bit is 1, the sorted numbers will be display in ascending order 
(5, 6, 10, 14) in the simulation window one after the other through the output partE.


 

