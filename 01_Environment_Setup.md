01_Environment_Setup.md

# Environment Setup for Reverse Engineering Labs

Inspired by "Reversing: Secrets of Reverse Engineering – Eldad Eilam"

The goal of this first step is to create a safe, reproducible environment to experiment with binaries, disassembly, and dynamic analysis.

---

## Recommended Tools

- Ghidra – Open-source reverse engineering suite  
- Radare2 / Cutter – Lightweight disassembler & analysis  
- IDA Free – Optional, classic disassembler  
- Python 3 – For scripting automation  
- GCC / Clang – Compile test binaries  
- GDB / lldb – Dynamic analysis and debugging  

---

## Linux / Termux Setup Example

```bash
pkg update && pkg upgrade
pkg install python clang git gdb radare2
