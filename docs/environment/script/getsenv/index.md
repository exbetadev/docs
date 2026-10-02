# getsenv

Returns the environment table of a running script.

```lua
getsenv(script: Instance): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Instance` | The script to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | The script environment, or `nil`. |

## Example

```lua
local env = getsenv(script)
print(env)
```
