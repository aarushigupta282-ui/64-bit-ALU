# 64-bit-ALU
Complete ASIC design flow of a 64-bit ALU, from RTL (Verilog) through logic synthesis, floorplanning, placement &amp; routing, timing closure, and GDSII generation.

# 64-bit ALU – Complete ASIC Flow

This project implements a **64-bit Arithmetic Logic Unit (ALU)**, designed and verified through the **complete ASIC design flow**, starting from RTL coding to final GDSII layout.

The ALU supports a wide range of **arithmetic and logical operations**, making it a critical component in CPUs, DSPs, and other digital systems. The project demonstrates practical application of **VLSI design principles**, with an emphasis on timing closure, power optimization, and physical design.

### Key Features
- Designed in **Verilog HDL** at RTL level.  
- Verified functionality through **testbenches and waveform simulations**.  
- Synthesized into a gate-level netlist using industry tools.   
- Completed **Place & Route (P&R)** with optimized placement and clock tree synthesis.  
- Generated final **GDSII layout**, which is DRC-clean and LVS-verified.  

### Tools & Technologies Used
- **RTL Design & Simulation:** Verilog, ModelSim / Icarus Verilog  
- **Synthesis & STA:** Synopsys Design Compiler / Yosys, OpenSTA  
- **Physical Design:** Cadence Innovus / OpenROAD  
- **Verification:** DRC, LVS checks with Magic/Calibre  

This project reflects the **end-to-end VLSI design cycle**, making it a strong reference for learning and for showcasing skills relevant to ASIC design roles.
