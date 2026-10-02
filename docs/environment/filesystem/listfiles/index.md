# listfiles

Lists the entries of a workspace folder.

```lua
listfiles(path: string?): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string?` | Folder to list. Defaults to the workspace root. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of entry names, relative to the workspace root. |

## Example

```lua
for _, name in ipairs(listfiles("scripts")) do
    print(name)
end
```
