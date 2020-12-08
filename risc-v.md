# RISC-V 笔记

+ 无条件跳转 (unconditional Jump) -- 2条:

        1. jal (Jmp and Link) : 立即跳转。可以用于调用子程序, 同时将返回地址存入"链接寄存器 (Link Reg)"。
        2. jalr (Jmp and Link Ret) : 基址+偏移跳转。用于子程序返回, 将 jal 指令保存的返回地址作为 jalr 指令的基址寄存器。

+ 条件跳转 (conditional branch) -- 6条:

        1. BEQ : 相等时跳转
        2. BNE : 不相等时跳转
        3. BLT : 小于时跳转 (对于有符号数)
        4. BLTU : 小于时跳转 (对于无符号数)
        5. BGE : 大于时跳转 (对于有符号数)
        6. BGEU ： 大于时跳转 (对于无符号数)
