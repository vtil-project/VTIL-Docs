---
description: Emits an arbitrary instruction into the instruction stream.
---

# VEMIT

| Instruction | Operand 1 | Description |
| :--- | :--- | :--- |
| VEMIT | Imm | Emits the opcode as is to the final instruction stream |

```cpp
// Emits '.' as instruction; see Brainfuck print instructions
block->vemit('.');
```

