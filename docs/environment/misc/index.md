---
icon: lucide/puzzle
---

---
tags:
  - Misc
---

# Misc

Executor identity, environments and helper functions.

| Function | Description |
| --- | --- |
| [`identifyexecutor`](identifyexecutor/index.md) | Returns the executor name. |
| [`getexecutorname`](getexecutorname/index.md) | Returns the executor name and version. |
| [`getgenv`](getgenv/index.md) | Returns the persistent executor global environment. |
| [`getrenv`](getrenv/index.md) | Returns the global environment of the Roblox state. |
| [`getreg`](getreg/index.md) | Returns the Lua registry table. |
| [`getmenv`](getmenv/index.md) | Returns the environment of a ModuleScript. |
| [`setfpscap`](setfpscap/index.md) | Sets the client frame rate cap. |
| [`getfpscap`](getfpscap/index.md) | Returns the current frame rate cap. |
| [`queueonteleport`](queueonteleport/index.md) | Schedules code to run after the next teleport. |
| [`clearteleportqueue`](clearteleportqueue/index.md) | Clears every script queued with `queueonteleport`. |
| [`trampoline_call`](trampoline-call/index.md) | Calls a function through a trampoline, bypassing direct-call checks. |
