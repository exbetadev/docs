# oth.is_hooked

Checks whether a function is currently hooked.

```lua
oth.is_hooked(fn: function): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the function is hooked. |

## Example

```lua
print(oth.is_hooked(old)) -- true
```
