<h1 align="center">Dhanush</h1>
<h3 align="center">RTL Design &amp; Verification Engineer</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/dhanush-71b36841b"><img src="https://img.shields.io/badge/LinkedIn-Dhanush-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:dhanushraj0703@gmail.com"><img src="https://img.shields.io/badge/Email-dhanushraj0703%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Bangalore%2C%20India-555555?style=flat" alt="Bangalore, India">
</p>

---

## About

RTL Design & Verification Engineer specializing in **Verilog RTL design**, **SystemVerilog**, **UVM**, **SVA** and **coverage-driven verification**, trained across the full ASIC flow at Maven Silicon.

- Designed an **AMBA APB-to-SPI master core** in Verilog and delivered lint-clean RTL with SpyGlass.
- Built a **UVM testbench with a multi-FIFO scoreboard** for a **2-master, 3-slave AXI interconnect**.
- Verified the APB-to-SPI core with a **UVM RAL model**, and verified a **dual-port RAM** with a SystemVerilog layered testbench.
- Closed functional coverage with covergroups: **100%** on the dual-port RAM and **95.45%** on the APB-to-SPI UVM environment, using Synopsys VCS, Verdi, URG and QuestaSim.

---

## Projects

| Project | Type | Highlights | Tools |
|---|---|---|---|
| **[AXI Interconnect Verification (2 Master – 3 Slave)](https://github.com/Dhanush30-DV/AXI-Interconnect-UVM-Verification)** | UVM Verification | 2 master + 3 slave agents, reset agent, multi-FIFO scoreboard with per-ID matching and address-decode checks, parallel and same-slave (arbitration) tests, 23 SVA properties; 24/24 regression runs pass, 96.52% functional coverage, 95.57% assertion coverage | SystemVerilog, UVM, SVA, QuestaSim, Make |
| **[APB Interface with Master SPI Core](https://github.com/Dhanush30-DV/APB-SPI-UVM-Verification)** | UVM Verification | Active APB and SPI agents, virtual sequencer, scoreboard checking PWDATA↔MOSI and PRDATA↔MISO, sequences for all four SPI modes (CPOL/CPHA) in LSB- and MSB-first order, APB protocol assertions; 95.45% functional coverage, 90.21% line coverage | SystemVerilog, UVM, VCS, Verdi, URG |
| **[Dual-Port RAM Verification](https://github.com/Dhanush30-DV/Dual-Port-RAM-SV-Verification)** | SystemVerilog Verification | Layered class-based testbench (generator, separate read/write drivers and monitors), reference model with read-before-write collision modelling, self-checking scoreboard, 3 tests including a same-address collision test; 100% functional coverage (15/15 bins), 0 mismatches | SystemVerilog, QuestaSim, Make |
| **[APB Interface with Master SPI Core](https://github.com/Dhanush30-DV/APB-SPI-Master-RTL-Design)** | RTL Design | FSM-based controller, APB slave interface, programmable baud-rate generator (CPOL/CPHA), full-duplex shift-register datapath, transfer-complete interrupt; lint-clean RTL (0 errors, 0 latches); synthesized with timing met at 50 MHz | Verilog, VC SpyGlass, Design Compiler, VCS, Verdi |

---

## Technical Skills

| Area | Skills |
|---|---|
| **Languages** | SystemVerilog, Verilog |
| **Verification Methodology** | UVM (Universal Verification Methodology), Register Abstraction Layer (RAL), Constrained-Random Verification (CRV), SystemVerilog Assertions (SVA), Functional Coverage, Code Coverage |
| **Design & Timing** | RTL Linting, Synthesis, Static Timing Analysis (STA) |
| **Protocols** | AMBA AXI (Multi-Master/Multi-Slave Interconnect), AMBA APB, SPI (Serial Peripheral Interface) |
| **EDA Tools** | Synopsys VCS, Verdi, Synopsys SpyGlass, QuestaSim, Xilinx Vivado |
| **VLSI Design Fundamentals** | Digital Electronics & Logic Design, CMOS & Semiconductor Basics |
| **Scripting & Platforms** | Linux (command line), GitHub |

---

## Training

**Advanced VLSI Design & Verification — Maven Silicon Softech Pvt. Ltd., Bangalore**
- Full ASIC flow, from RTL coding to UVM verification closure, including multi-agent SoC-level testbenches.
- Synthesizable Verilog RTL for AMBA APB, AXI and SPI, checked with RTL lint; SystemVerilog/UVM testbenches with CRV, coverage and SVA.
- Static Timing Analysis: setup/hold checks, timing report analysis and timing closure in the ASIC/SoC sign-off flow.

## Education

**Bachelor of Engineering, Electronics & Communication Engineering** — AJ Institute of Engineering and Technology, Mangalore · CGPA 7.9/10 · 2025

---

<p align="center"><i>Open to RTL Design and Design Verification roles.</i></p>
