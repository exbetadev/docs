# getsignalwhitelist

Returns the allowlist of signals that may be replicated.

```lua
getsignalwhitelist(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of permitted signal names. |

## Example

```lua
local whitelist = getsignalwhitelist()
print(#whitelist)
```
