# getidentity

Returns the current thread identity level.

```lua
getidentity(): number
```

## Returns

| Type | Description |
| --- | --- |
| `number` | The identity level of the running thread. |

## Aliases

- `getthreadidentity`
- `getthreadcontext`

## Example

```lua
print(getidentity()) -- 8
```
