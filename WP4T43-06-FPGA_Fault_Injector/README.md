# WP4T43-06 FPGA Fault Injector (FFI)

FPGA fault injection is supported by the bit-accurate FFI tool (BAFFI).

## Description

BAFFI tool automates fault injection experiments in FPGA prototypes targeting Xilinx FPGAs.
BAFFI forms a part of the DAVOS toolkit.
The detailed tookit description is available in the DAVOS repository under the link: 
https://gitlab.com/selene-riscv-platform/DAVOS

BAFFI tool supports fine-grain hierarchical FFI experiments,
where each node in the DUT tree can be targeted with an accuracy of up to an individual netlist cell.

## Objectives

BAFFI satisfies the FRACTAL objectives by automating several dependability-driven processes of design flow, including:
* Verification of safety/security mechanisms of the FRACTAL node prototype (at the hardware layer, e.g. SELENE platform);
* Assessing the dependability (safety) features of the FRACTAL node;
* Identifying the dependability (safety) bottlenecks of the FRACTAL node;
* Dependability benchmarking of design alternatives (safety mechanisms and IP cores).

## Prerequisites

BAFFI tool requires:
* Python version 2.x (basic distribution),
* Xilinx Vivado suite version 2020 and later.

## Installation and usage
Installation and usage steps are described in the readme file of the DAVOS repository.
