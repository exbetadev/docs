# Regex:Match

Finds the first match and returns its captures.

```lua
regex:Match(text: string): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `string` | The string to search. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | Array of captures `{ Full, Groups = {...} }`, or `nil` when no match. |

## Example

```lua
local match = regex:Match("abc123")
if match then
    print(match.Full) -- 123
end
```
