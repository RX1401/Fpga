# Fpga
This repository is about my recent fpga project
The Voting System in Verilog is a digital circuit that registers and counts votes using combinational and sequential logic. It ensures a secure and reliable voting process through flip-flops, multiplexers, and finite state machines (FSM).

Implementation Details:
Inputs: Candidate selection (sel), vote signal (vote), and reset (reset).

Processing:

A finite state machine (FSM) manages voting sequences.

Registers store vote counts for each candidate.

Debouncing logic prevents false triggers from mechanical switches.

One-vote-per-user logic ensures fairness.

Outputs: Vote count displayed on seven-segment displays or LEDs.

Key Modules:
Vote Controller – Manages voting state and ensures only one vote per session.

Counter Module – Increments vote count for selected candidates.

Display Module – Outputs results on an FPGA board or simulation environment.

Applications:
This Verilog-based voting system is ideal for FPGA implementation, small-scale elections, and learning digital design principles like FSMs, counters, and sequential logic.









