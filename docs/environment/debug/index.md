---
icon: lucide/folder
---

---
tags:
  - Debug
---

# Debug

Inspect and edit upvalues, constants, prototypes and the call stack.

| Function | Description |
| --- | --- |
| [`getupvalues`](getupvalues/index.md) | Returns every upvalue of a function. |
| [`getupvalue`](getupvalue/index.md) | Reads a single upvalue by index. |
| [`setupvalue`](setupvalue/index.md) | Writes a single upvalue by index. |
| [`getconstants`](getconstants/index.md) | Returns all constants of a function. |
| [`getconstant`](getconstant/index.md) | Reads a single constant by index. |
| [`setconstant`](setconstant/index.md) | Replaces a constant, which rewrites string and number literals. |
| [`getproto`](getproto/index.md) | Returns one nested prototype of a function. |
| [`getprotos`](getprotos/index.md) | Returns every nested prototype of a function. |
| [`getstack`](getstack/index.md) | Reads a variable from the call stack. |
| [`setstack`](setstack/index.md) | Overwrites a variable in the call stack. |
| [`getinfo`](getinfo/index.md) | Returns debug information for a function or stack level. |
