# linux
I'm using Ubuntu.

## basic terminal stuff

| command | result |
| --- | --- |
| `... \| less` | pipe to less, for displaying text. Space = next page, b = last page, q = quit |
| `ps -a`, `kill <pid>`, `kill -9 <pid>` | kill a process |
| `Shift + Strg + W` | close window |
| `Super + D` | minimize/maximize all |
| `Strg + W` | close tab |
| `grep -- -O` | the two -- tells grep that the rest are not options |
| `<command> &` | creates a background process, so you can continue in shell |

## coding
### general

| command | result |
| --- | --- |
| `strings` | prints all strings in a file (also executables) |
| `objdump -d -M intel` | disassemble .text, intel syntax (-D disassembles all) |
| `strace` | display system calls of commands/programs |
| `ltrace` | display library calls |
| `echo $?` | echo error code of last run program (0 means no error) |
| `strip` | remove all symbols of executables -> faster and difficult to recreate |

### gcc

| command | result |
| --- | --- |
| `gcc -c` | c flag means compile, don't link (you can compile without main) |
| `gcc -O3` | 01 optimize, 02 more optimize, 03 most optimize |
| `gcc -Wall` | enable warnings |
| `gcc -g` | produce debugging info |

### gdb

| command | result |
| --- | --- |
| `[gdb] layout regs` | show registers, disassembly and normal terminal |
| `[gdb] i r` | print registers |
| `[gdb] help x` | show examine options |
| `[gdb] x $rax` | examine a register |
| `[gdb] i r rax rbp` | shows registers |
| `[gdb] disas` | show disassembly |
| `[gdb] ni/si` | next instruction / step instruction ("step into") |

