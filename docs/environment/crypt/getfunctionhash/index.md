# getfunctionhash

Computes a hash representing the function's bytecode.

```lua
getfunctionhash(fn: function): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to hash. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Hash in hex. |

## Example

```lua
print(getfunctionhash(print))
```
