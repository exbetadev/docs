---
icon: lucide/file-code
---

---
tags:
  - Script
---

# Script

Inspect scripts, their bytecode and environments.

| Function | Description |
| --- | --- |
| [`getscripts`](getscripts/index.md) | Returns all client-side scripts currently loaded. |
| [`getrunningscripts`](getrunningscripts/index.md) | Returns scripts that have started execution. |
| [`getloadedmodules`](getloadedmodules/index.md) | Returns every ModuleScript that has been required. |
| [`getscriptbytecode`](getscriptbytecode/index.md) | Returns the compiled bytecode of a script. |
| [`getscriptfromthread`](getscriptfromthread/index.md) | Returns the script that owns a coroutine. |
| [`getscriptclosure`](getscriptclosure/index.md) | Returns a callable closure for a script's body. |
| [`getcallingscript`](getcallingscript/index.md) | Returns the script that invoked the current function. |
| [`getsenv`](getsenv/index.md) | Returns the environment table of a running script. |
| [`getgc`](getgc/index.md) | Scans the garbage collector for live objects. |
| [`getallthreads`](getallthreads/index.md) | Returns all live coroutines. |
| [`filtergc`](filtergc/index.md) | Filters garbage-collected objects by type and criteria. |
