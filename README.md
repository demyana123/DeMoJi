# DeMoJi
dual-RvCore processor

DeMoJi is 32-bit dual-RvCore. It supports Multiplication,Division and atomic instructions. The processor is written in Systemverilog and designed to support multiple customized peripheral devices.

It is derived from Taiga as single RvCore, if you want to see it, visit:

https://gitlab.com/sfu-rcl/Taiga

Simulation Environment:

If you want to simlate on Veilator tool, all simulation steps and this tool are available on the previous link. DeMoJi is simulated on Vivado 2020.2 tool because Vivado 2018 causes some issues on simulation, take care to change the path of your directory in testbench file otherwise the program doesn't work. 

Testing:

Different C codes run on this processor and their results are shown under c-code and waveforms file. Also, CoreMark tool is simulated on DeMoJi multiprocessor  

Communication:

for any inquiry, you can send on: Dem11@fayoum.edu.eg

