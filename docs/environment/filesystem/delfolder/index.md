# delfolder

Deletes a folder and its contents.

```lua
delfolder(path: string): (nil?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Example

```lua
delfolder("temp")
```

!!! note "Protected"
    The workspace root itself cannot be deleted.
