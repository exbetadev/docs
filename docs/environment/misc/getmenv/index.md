# getmenv

Returns the environment of a ModuleScript.

```lua
getmenv(module: Instance): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `module` | `Instance` | The ModuleScript to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | Module environment, or `nil`. |

## Example

```lua
local env = getmenv(module)
print(env)
```
