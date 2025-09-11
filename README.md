# RISC-V Architecture

## 🧩 Overview  
This repository tracks my progress building a **RISC-V processor**.  
I have **already completed a single-cycle core**, and this project continues that work by implementing a **5-stage pipelined architecture** to improve instruction throughput and efficiency.

## 🔗 Features (Planned/Implemented)  
- ✅ Single-cycle RV32I core (completed earlier)  
- 🚧 5-stage pipeline: IF → ID → EX → MEM → WB (in progress)  
- 🚧 Pipeline registers between all stages  
- 🚧 Hazard handling: Data forwarding, stall/flush logic for load-use and branch hazards  
- 🚧 Branch control with basic flush or early resolution  
- Planned verification with sample RISC-V assembly programs

## 📜 Flow of Work  
1. **Single-cycle Core** – Finished and tested as the foundation.  
2. **Pipeline Planning** – Reviewed tutorials and sketched pipeline partitioning.  
3. **Pipeline Registers** – Split datapath into stages and inserted IF/ID, ID/EX, EX/MEM, MEM/WB registers.  
4. **Control Signal Adjustments** – Propagate control signals through pipeline stages.  
5. **Hazard Detection & Forwarding** – Implement forwarding, stall, and flush logic.  
6. **Branch Handling** – Add control hazard management.  
7. **Testing & Verification** – Run RISC-V programs and compare with a reference simulator.  
8. **Documentation & Cleanup** – Finalize code comments and README updates.

## 📂 File Structure  
