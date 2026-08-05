# 1x4 Demultiplexer using Verilog

## Objective
To design and simulate a 1x4 Demultiplexer using Verilog HDL.

## Description
A 1x4 Demultiplexer routes one input signal to one of four outputs based on two select lines. The selected output follows the input, while all other outputs remain 0.

## Truth Table

| S1 | S0 | Y3 | Y2 | Y1 | Y0 |
|----|----|----|----|----|----|
| 0  | 0  | 0  | 0  | 0  | I  |
| 0  | 1  | 0  | 0  | I  | 0  |
| 1  | 0  | 0  | I  | 0  | 0  |
| 1  | 1  | I  | 0  | 0  | 0  |

## Files
1. demux1x4.v      - Verilog design code
2. demux1x4_tb.v   - Testbench
3. README.md       - Project documentation

## Software Required
- Xilinx Vivado
- ModelSim
- Icarus Verilog
- GTKWave (optional)

## How to Run
1. Compile demux1x4.v and demux1x4_tb.v.
2. Run the simulation.
3. Observe the waveform and verify the outputs.

## Expected Result
The input signal should appear only at the selected output according to the select lines, while the remaining outputs stay LOW.