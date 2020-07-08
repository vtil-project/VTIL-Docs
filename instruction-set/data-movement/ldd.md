---
description: >-
  Dereferences a register and loads the value into a register. The source
  register supports offsets.
---

# LDD

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| LDD | Reg | Reg | Imm | OP1 &lt;= \[OP2+OP3\] |

```cpp
// Creates a temporary register and loads [REG_SP+0] into it.
auto value = block->tmp(8);
block->ldd(value, REG_SP, 0);
```

