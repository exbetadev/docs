# restorefunction

Restores a function previously replaced by hookfunction.

```lua
restorefunction(hooked: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `hooked` | `function` | A function that was hooked earlier. |

## Returns

| Type | Description |
| --- | --- |
| `function` | The restored original function. |

## Aliases

- `restorefunc`

## Example

```lua
hookfunction(print, function() end)
restorefunction(print)
print("restored") -- prints normally again
```
