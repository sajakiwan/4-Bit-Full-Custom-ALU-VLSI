# 4-Bit Full-Custom ALU – VLSI Design & Verification

## Overview
A complete 4-bit full-custom Arithmetic Logic Unit (ALU) designed, implemented, and extensively verified using Cadence Virtuoso.

The project covers the full custom-design process from transistor-level circuit design and hierarchical integration to physical layout, parasitic extraction, post-layout verification, timing characterization, statistical robustness analysis, and PPA evaluation.

The ALU integrates arithmetic, logic, comparison, and status-flag functionality into a complete 4-bit architecture.

## Architecture & Design

The system was developed hierarchically from custom-designed building blocks and integrated into a complete 4-bit ALU.

### Main Building Blocks
- Full Adder
- XOR Gate
- AND Gate
- OR Gate
- NOT Logic
- 2:1 Multiplexer
- 4:1 Multiplexer
- Arithmetic Unit
- Logic Unit
- 1-bit ALU Cell
- 4-bit ALU

## Supported Functionality

The ALU was designed and verified for multiple arithmetic and logic operations, including:

- ADD
- SUB
- AND
- OR
- XOR
- NOT
- SET
- Signed SLT (Set Less Than)

Additional functionality includes:

- Carry propagation
- Signed Overflow detection
- Zero Flag detection
- Comparison logic

## Functional Verification

Extensive transient simulations were performed to verify the operation of the complete system and its individual blocks.

Verification included:

- Logic-unit operation verification
- Arithmetic-unit verification
- ADD and SUB functionality
- Carry propagation analysis
- Positive Overflow
- Negative Overflow
- No-Overflow cases
- Zero Flag assertion and de-assertion
- Signed SLT for A < B and A ≥ B
- SET functionality

## Timing Analysis

The design was characterized using propagation-delay measurements across relevant signal paths.

The analysis included:

- Rise and fall propagation delays
- Delay threshold definition
- Carry-chain timing
- Flag timing
- SLT timing
- Critical-path analysis
- Worst-case timing behavior

## Monte Carlo & Statistical Robustness

Monte Carlo simulations were used to evaluate circuit robustness under process and mismatch variations.

The statistical analysis included:

- Process variation
- Device mismatch
- Delay distributions
- Histograms
- Pass/Fail classification
- Yield evaluation
- Identification of the statistically most sensitive timing path
- Verification of worst-case simulation runs

## Pre-Layout vs. Post-Layout Analysis

Pre-layout and extracted post-layout simulations were compared to quantify the impact of parasitic effects.

The comparison included:

- ADD and carry chain
- SUB
- OR
- Zero Flag
- Overflow Flag
- Propagation delay

This analysis was used to evaluate the effect of extracted parasitic resistance and capacitance on circuit timing and performance.

## Physical Design & Verification

A full-custom physical layout of the 4-bit ALU was implemented and verified.

Physical verification included:

- Layout implementation
- DRC – Design Rule Check
- LVS – Layout Versus Schematic
- PEX – Parasitic Extraction
- Post-layout simulation

## PVT & PPA Analysis

The final design was evaluated across Process, Voltage, and Temperature conditions to assess robustness under different operating corners.

The analysis included:

- PVT corner simulations
- Pre-layout vs. post-layout performance
- Propagation delay
- Layout area
- Power consumption
- Power-Delay Product (PDP)
- Energy-Delay Product (EDP)
- Overall PPA and robustness evaluation

## Tools & Methodologies

- Cadence Virtuoso
- Full-Custom VLSI Design
- CMOS Circuit Design
- Schematic Design
- Physical Layout
- Transient Simulation
- Timing Analysis
- DRC / LVS
- PEX
- Pre/Post-Layout Analysis
- Monte Carlo Analysis
- Process & Mismatch Analysis
- PVT Analysis
- PPA Analysis

## Skills Demonstrated

Full-Custom VLSI • CMOS Design • Digital IC Design • Physical Layout • Physical Verification • DRC • LVS • PEX • Circuit Simulation • Timing Analysis • Statistical Verification • Monte Carlo Analysis • PVT Analysis • PPA Analysis • Power Analysis • Robustness Analysis