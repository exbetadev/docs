---
icon: lucide/layers
---

---
tags:
  - Metatable
---

# Metatable

Read and modify metatables, hook metamethods.

| Function | Description |
| --- | --- |
| [`getrawmetatable`](getrawmetatable/index.md) | Returns an object's metatable, bypassing __metatable protection. |
| [`getrawmetatable_from_class`](getrawmetatable-from-class/index.md) | Returns the shared metatable for an instance class name. |
| [`setrawmetatable`](setrawmetatable/index.md) | Replaces an object's metatable, bypassing __metatable protection. |
| [`setreadonly`](setreadonly/index.md) | Sets or clears the read-only flag on a table. |
| [`isreadonly`](isreadonly/index.md) | Checks whether a table is read-only. |
| [`makereadonly`](makereadonly/index.md) | Locks a table against writes. |
| [`makewriteable`](makewriteable/index.md) | Unlocks a read-only table. |
| [`hookmetamethod`](hookmetamethod/index.md) | Hooks a single metamethod on an object and returns the original. |
| [`firemetamethod`](firemetamethod/index.md) | Invokes a metamethod directly. |
| [`getnamecallmethod`](getnamecallmethod/index.md) | Returns the method name of the active __namecall. |
| [`getidentity`](getidentity/index.md) | Returns the current thread identity level. |
| [`setidentity`](setidentity/index.md) | Sets the current thread identity level. |
