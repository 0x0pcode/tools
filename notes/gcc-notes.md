# GCC notes

- Specify arguments
  - `gcc --args program arg1 arg2` 

- `info stack`
  - Show the stack

- `info registers`
  - Show the registers

- `info functions`
  - list all functions (symbols)

- `x/i` address/symbol
  - dump as instruction
  - `x/20i test` - list 20 instructions

- `set disassembly-flavor intel`
  - Set disassembly to Intel syntax
  - add it to ~/.gdbinit to automatically set it to Intel syntax every time you run GDB

- `(gdb) info line main`
  - Show information about function including start and end address

- `(gdb) disas STARTADDRESS ENDADDRESS`
  - Disassembly the function from start to end addresses




