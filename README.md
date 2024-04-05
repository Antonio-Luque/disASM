# disASM
![Screenshot](https://github.com/Antonio-Luque/disASM/blob/main/disASM.png)

A Disassembler for ZX Spectrum. Based on Disassembler support from Small Computer Monitor ([SCM](https://smallcomputercentral.com/small-computer-monitor/small-computer-monitor-v1-0/ )) by Stephen C Cousins.

### Features:
- Can be loaded at any RAM address (below the System Variables).
- Uses an internal stack.
- Recognizes undocumented opcodes related to IXH, IXL, IYH and IYL registers.
- Needs less than 2 Kbytes of RAM.

### Usage:
1. LOAD ""CODE \<address\> (default: 57600)
2. RANDOMIZE USR \<address\>
3. Input "from" address (in hexadecimal) to start disassembly and "to" address (in hexadecimal) to end disassembly.
