# trampoline_call

Calls a function through a trampoline, bypassing direct-call checks.

```lua
trampoline_call(fn: function, args: table): ...any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to invoke. |
| `args` | `table` | Arguments passed to the function. |

## Returns

| Type | Description |
| --- | --- |
| `...any` | The function's return values. |

## Example

```lua
local result = trampoline_call(fn, { 1, 2, 3 })
print(result)
```
