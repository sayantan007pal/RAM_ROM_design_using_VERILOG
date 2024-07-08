# RAM_ROM_design_using_VERILOG

Verilog Memory Modules and Testbenches

Description

This project contains Verilog modules for various types of memory designs, including Single Port RAM, Dual Port RAM, and ROM, along with their respective testbenches for simulation and verification.

Modules

1.Single Port RAM (single_port_ram.v):

  a. A simple RAM with 64x8-bit memory.
  b. Supports read and write operations on a single port.
  
2. Dual Port RAM (dual_port_ram.v):

 a. A RAM with 64x8-bit memory.
 b. Supports simultaneous read/write operations on two ports.
 
3. ROM (rom.v):

 a. A ROM with 16x4-bit memory.
 b. Outputs pre-stored data based on the address input.
 
Testbenches

1. Single Port RAM Testbench (single_port_ram_tb.v):

 a. Initializes clock and stimulus.
 b. Verifies read and write operations by observing the output.
 
2. Dual Port RAM Testbench (dual_port_ram_tb.v):

 a.Initializes clock and stimulus.
 b.Verifies simultaneous read/write operations on both ports.
 
3. ROM Testbench (rom_tb.v):

 a. Initializes clock and stimulus.
 b. Verifies ROM outputs based on various addresses and enable signals.
 
Usage

Simulation:

1. Compile and simulate the Verilog files using a simulator like ModelSim or Vivado.
2. Use the testbenches to verify functionality.
3. Observe the waveforms using the generated VCD files.
4. 
Compilation:

1. Ensure the main modules and testbenches are in the same directory.
2. Run the testbenches to check for correct operation and timing.
3. 
Conclusion

These memory module designs and testbenches provide a foundation for understanding and implementing memory operations in Verilog. The testbenches ensure functionality and correctness of the modules, making them suitable for educational and practical applications in digital design.








