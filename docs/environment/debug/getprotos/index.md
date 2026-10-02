# getprotos

Returns every nested prototype of a function.

```lua
getprotos(fn: function): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The enclosing function. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of nested functions. |

## Example

```lua
for _, proto in ipairs(getprotos(fn)) do
    print(proto)
end
```
