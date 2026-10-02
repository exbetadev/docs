---
icon: lucide/webhook
---

---
tags:
  - Oth
---

# Oth

Yield-safe hooks for native Roblox functions.

| Function | Description |
| --- | --- |
| [`oth.hook`](oth-hook/index.md) | Hooks a function while preserving coroutine yielding. |
| [`oth.unhook`](oth-unhook/index.md) | Removes a hook previously installed with `oth.hook`. |
| [`oth.is_hooked`](oth-is-hooked/index.md) | Checks whether a function is currently hooked. |
| [`oth.get_hook`](oth-get-hook/index.md) | Returns the replacement function attached to a hook. |
| [`oth.replace_hook`](oth-replace-hook/index.md) | Replaces the hook function without unhooking the target. |
| [`oth.get_root_callback`](oth-get-root-callback/index.md) | Returns the original callback behind the current hook. |
| [`oth.is_hook_thread`](oth-is-hook-thread/index.md) | Checks whether the current context is a hook thread. |
| [`oth.get_original_thread`](oth-get-original-thread/index.md) | Returns the thread the hook was called from. |
