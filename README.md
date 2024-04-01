# disASM
![Screenshot](https://github.com/Antonio-Luque/disASM/blob/main/disASM.png)

A Disassembler for ZX Spectrum. Based on Small Computer Monitor ([SCM](https://smallcomputercentral.com/small-computer-monitor/small-computer-monitor-v1-0/ )) by Stephen C Cousins.

### Features:
- Can be loaded at any RAM address (below the System Variables).
- Use an internal stack.
- Recognizes undocumented opcodes related to IXH, IXL, IYH and IYL registers.
- Need only 2 Kbytes of RAM.

### Usage:
- LOAD ""CODE \<address\> (default: 57600)
- RANDOMIZE USR \<address\>
- Input "from" address (in hexadecimal) to start disassembly and "to" address (in hexadecimal) to end disassembly.
