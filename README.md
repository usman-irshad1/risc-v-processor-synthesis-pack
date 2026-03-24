# Risc V Processor Synthesis Pack

RISC-V processor top module, unified memory, and synthesis verification suite

## Architecture & Project Modules
This repository contains the hardware description and simulation models developed in SystemVerilog/Verilog using AMD/Xilinx Vivado.

### Primary Verilog & Support Files
- `immediate_gen.sv`
- `pc_reg.sv`
- `reg.mem`
- `unified_memory.mem`
- `Unified_mem.sv`
- `ALU_reg.sv`
- `data_reg.sv`
- `Instruction_reg.sv`
- `reg.sv`
- `ALU.sv`
- `alu_control.sv`
- `alu_out.sv`
- `ALU_source1.sv`
- `ALU_Source_2.sv`
- `Mul.sv`
- `mul_mux.sv`
- `mux_mul.sv`
- `Control.sv`
- `adress_source.sv`
- `write_back.sv`
- `tb_top_processor_time_impl.v`
- `Top.sv`
- `tb.sv`

## Build & Simulation Instructions
1. Open **AMD/Xilinx Vivado** (or ModelSim / Icarus Verilog).
2. Create a new Vivado RTL Project.
3. Add the Verilog/SystemVerilog source files located in this repository.
4. Set the top-level module (e.g. `TOP.sv` or top module) as the Top Module.
5. Run Behavioral Simulation via `xsim` or launch Synthesis/Implementation.

## Author & Maintainer
- **Author**: Mohammad Usman Irshad
- **GitHub Profile**: [@usman-irshad1](https://github.com/usman-irshad1)
