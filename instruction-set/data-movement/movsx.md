---
description: Moves an immediate value or register with sign extension into a register.
---

# MOVSX

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| MOVSX | Reg | Reg/Imm | OP1 = SX\(OP2\) |

```cpp
block->movsx(vtil::REG_SP, 1337);
```

