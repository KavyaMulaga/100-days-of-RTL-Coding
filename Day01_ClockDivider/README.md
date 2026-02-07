# Day 1 - Clock Divider

## Objective
Design a clock divider to generate lower frequency clocks from a single input clock.

## Inputs
- clk
- reset (synchronous, active high)

## Outputs
- clk_div2
- clk_div4
- clk_div8
- clk_div16

## Description
A 4-bit counter is used. Each bit of the counter toggles at half the frequency of the previous bit.
This effectively generates divided clocks.

## Tools Used
- Verilog
- ModelSim / GTKWave

## What I Learned
- Clock division using counters
- Writing synchronous reset logic
- Importance of simulation before synthesis
