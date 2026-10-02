# firemetamethod

Invokes a metamethod directly.

```lua
firemetamethod(object: any, method: string, ...: any): ...any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `any` | The target object. |
| `method` | `string` | Metamethod name to call. |
| `...` | `any` | Arguments forwarded to the metamethod. |

## Returns

| Type | Description |
| --- | --- |
| `...any` | Whatever the metamethod returns. |

## Example

```lua
local value = firemetamethod(game, "__index", "Players")
print(value) -- Players
```
