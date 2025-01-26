# VHDL Counter Bug and Solution

This repository demonstrates a common VHDL coding error in a simple counter and provides a corrected version.

## Bug Description
The `buggy_counter.vhdl` file contains a counter that might suffer from issues due to clock glitches or unexpected reset behavior. The original implementation is prone to unpredictable counts if the reset signal is noisy or the clock isn't clean.

## Solution
The `fixed_counter.vhdl` provides a more robust implementation addressing the potential issues outlined above.  Improvements include more reliable handling of the asynchronous reset and improved clock edge detection for robustness.

## How to use
1. Simulate both the buggy and fixed versions using a VHDL simulator (like ModelSim or GHDL).
2. Apply various clock and reset scenarios to observe the different behaviors.
3. Compare the simulation results to confirm the fix's effectiveness.