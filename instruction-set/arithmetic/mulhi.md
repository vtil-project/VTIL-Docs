---
description: >-
  Multiplies a register with another register or immediate value and saves the
  higher 16 bits.
---

# MULHI

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| MULHI | Reg | Reg/Imm | OP1 = \[OP1 × OP2\] &gt;&gt; N |

```cpp
block->mulhi(vtil::REG_SP, 2);
```

