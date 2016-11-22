## Assemble

### intel 80x86体系架构

- 寄存器
  * 通用寄存器
  > eax, ebx, ecx, edx, esi, edi, ebp, esp (32位寄存器)
    * E: e代表扩展的意思(Extended)
    * ax, bx, cx, dx, si, di, bp, sp (16位寄存器)  ip cs ss ds es psw(8086寄存器)
    * al, ah, bl, bh, cl, ch, dl, dh (80x86 Cpu提供的8个8位寄存器)

    > 86x86 提供8个通用寄存器； 16个寄存器叠加于32位寄存器之上， 8位叠加于16位之上

  *特殊目的寄存器

  > eflags: 32位 溢出标志， 进位标志， 符号标志， 零标志 （这4个标志统称位条件码）


  * 段寄存器
  > 8086段寄存器: cs, ds, ss, es

    * cs: 代码段寄存器
    * ip: 指令指针寄存器
  *特殊目的核心模寄存器
  >

  1. 8086  CPU  
    - byte 8
    - word 16
