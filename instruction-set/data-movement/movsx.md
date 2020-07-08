---
description: Moves an immediate value or register with sign extension into a register.
---

# MOVSX

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| MOVSX | Reg | Reg/Imm | OP1 = SX\(OP2\) |

```cpp
block->mov(X86_REG_EAX, -1)
block->movsx(X86_REG_RAX, X86_REG_EAX); // rax = -1ll
```

