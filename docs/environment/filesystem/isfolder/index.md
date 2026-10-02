# isfolder

Checks whether a folder exists.

```lua
isfolder(path: string): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the folder exists. |

## Example

```lua
if not isfolder("scripts") then
    makefolder("scripts")
end
```
