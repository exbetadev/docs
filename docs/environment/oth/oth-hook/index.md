# oth.hook

Hooks a function while preserving coroutine yielding.

```lua
oth.hook(fn: function, hook: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to hook. |
| `hook` | `function` | Replacement function that may yield. |

## Returns

| Type | Description |
| --- | --- |
| `function` | The hooked function. |

## Example

```lua
local old = oth.hook(game.HttpGet, function(url)
    print("requesting", url)
    return old(url)
end)
```

!!! note "Yielding"
    The hook runs in a separate scheduler thread, so it can yield, wait and call task functions safely.
