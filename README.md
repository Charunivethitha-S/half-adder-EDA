# half-adder-EDA
A Verilog-based design and simulation of a Half Adder with complete RTL code, testbench, and simulation waveform. This project demonstrates fundamental combinational logic design and verification using industry-standard EDA tools.

**Project Contents**

1.RTL Code – Verilog implementation of the Half Adder

2.Testbench – Stimulus to verify Sum and Carry outputs

3.Waveform (JPG) – Simulation results proving design correctness

4.VCD Generation – Using $dumpfile and $dumpvars

**Half Adder Overview**

A Half Adder is a basic digital circuit that performs binary addition of two 1-bit inputs:
Sum = A ⊕ B

Carry = A · B

**Tools Used**

1. EDA Playground (Online Simulator)
2. HDL Language : Verilog 
3. Tools & Simulators : Aldec Riveria Pro 2023.04

**How to Run This Project**

1. Open the RTL (half_adder.v) and testbench (testbench.v) files.

2. Use any Verilog simulator (e.g., EDA Playground, ModelSim, QuestaSim).

3. Ensure you include in the testbench:

$dumpfile("dump.vcd");

$dumpvars(0, test_bench);


4. Run the simulation to generate dump.vcd.

5. View the waveform using EPWave or any VCD viewer.

**Output**

 The waveform image included in this repository (waveform.jpg) confirms:

1. Sum and Carry values follow the truth table

3. All input combinations are tested

The design behaves as expected
