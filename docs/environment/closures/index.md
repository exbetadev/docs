---
icon: lucide/braces
---

---
tags:
  - Closures
---

# Closures

Compile, hook, clone and inspect functions.

| Function | Description |
| --- | --- |
| [`loadstring`](loadstring/index.md) | Compiles Luau source into a callable function. |
| [`hookfunction`](hookfunction/index.md) | Replaces a function with your own and returns the original. |
| [`newcclosure`](newcclosure/index.md) | Wraps a Luau function so it reports as a C closure. |
| [`restorefunction`](restorefunction/index.md) | Restores a function previously replaced by hookfunction. |
| [`clonefunction`](clonefunction/index.md) | Creates an independent copy of a function. |
| [`iscclosure`](iscclosure/index.md) | Checks whether a value is a C closure. |
| [`islclosure`](islclosure/index.md) | Checks whether a value is a Luau closure. |
| [`isexecutorclosure`](isexecutorclosure/index.md) | Checks whether a function originates from the executor. |
| [`checkcaller`](checkcaller/index.md) | Checks whether the current call originates from executor code. |
| [`compareclosures`](compareclosures/index.md) | Compares two functions for equivalence. |
| [`isfunctionhooked`](isfunctionhooked/index.md) | Checks whether a function is currently hooked. |
| [`gettenv`](gettenv/index.md) | Returns the global environment of a thread. |
