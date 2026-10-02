# getallthreads

Returns all live coroutines.

```lua
getallthreads(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of threads. |

## Example

```lua
for _, thread in ipairs(getallthreads()) do
    print(thread)
end
```
