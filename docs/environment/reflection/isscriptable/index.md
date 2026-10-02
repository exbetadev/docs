# isscriptable

Checks whether a property can be accessed from scripts.

```lua
isscriptable(instance: Instance, property: string): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to test. |
| `property` | `string` | Property name. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the property is scriptable. |

## Example

```lua
print(isscriptable(workspace, "StreamingEnabled"))
```
