---
description: >-
  Multiplies a register with another register or immediate value and saves the
  higher bits.
---

# MULHI

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| MULHI | Reg | Reg/Imm | OP1 = \[OP1 × OP2\] &gt;&gt; N |

```cpp
block->mulhi(REG_SP, 2);
```

