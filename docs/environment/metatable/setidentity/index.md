# setidentity

Sets the current thread identity level.

```lua
setidentity(level: number): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `number` | The identity level to apply. |

## Aliases

- `setthreadidentity`
- `setthreadcontext`

## Example

```lua
setidentity(8)
print(getidentity()) -- 8
```
