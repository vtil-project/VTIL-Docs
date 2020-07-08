---
description: >-
  Stores a register or immediate value in the dereferenced value of a register.
  The destination register supports offsetting.
---

# STR

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| STR | Reg | Imm | Reg/Imm | \[OP1+OP2\] &lt;= OP3 |

```cpp
// Stores 1337 into [REG_SP+0]
block->str(REG_SP, 0, 1337);
```

