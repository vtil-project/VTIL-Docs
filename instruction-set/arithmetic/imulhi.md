---
description: >-
  Multiplies a register with another register or immediate value and saves the
  higher bits. This operation is signed.
---

# IMULHI

| Instruction | Operand 1 | Operand 2 | Description |
| :--- | :--- | :--- | :--- |
| IMULHI | Reg | Reg/Imm | OP1 = \[OP1 × OP2\] &gt;&gt; N \(Signed\) |

```cpp
block->imulhi(REG_SP, 2);
```

