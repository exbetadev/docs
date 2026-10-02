# setscriptable

Makes a property scriptable or non-scriptable.

```lua
setscriptable(instance: Instance, property: string, enabled: boolean): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to modify. |
| `property` | `string` | Property name. |
| `enabled` | `boolean` | `true` to enable scripting, `false` to disable. |

## Example

```lua
setscriptable(workspace, "StreamingEnabled", true)
workspace.StreamingEnabled = false
```
