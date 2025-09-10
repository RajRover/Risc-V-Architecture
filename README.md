# 🖥️ RISC-V Architecture in Verilog  

This repository contains my Verilog-based **RISC-V CPU implementation**. It starts with a **single-cycle processor** and will later be extended to include a **five-stage pipelined processor** for improved performance and instruction throughput.  

---

## 📌 Features  
- **RV32I Single-Cycle CPU**  
  - Implements core RISC-V instructions.  
  - Includes ALU, register file, instruction memory, and data memory.  
- **Pipelined CPU (Planned)**  
  - Five stages: IF, ID, EX, MEM, WB.  
  - Hazard detection, forwarding logic, and pipeline stall handling.  
- **Testbenches and Verification**  
  - Includes simulation test programs for functional validation.  
- **Modular Design**  
  - Separated modules for better readability and scalability.  

---

## 🏗️ Architecture Overview  

### Single-Cycle CPU  

[Instruction Memory] --> [Control Unit] --> [ALU] --> [Data Memory]
| ↑
↓ |
[Register File] <--------------



### Planned Five-Stage Pipeline  
- **IF (Instruction Fetch):** Fetch instructions from memory.  
- **ID (Instruction Decode):** Decode and read registers.  
- **EX (Execute):** Perform ALU operations.  
- **MEM (Memory Access):** Load/store data.  
- **WB (Write Back):** Write results back to registers.  

---












