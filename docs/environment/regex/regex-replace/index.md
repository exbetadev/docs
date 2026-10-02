# Regex:Replace

Replaces every match with the replacement string.

```lua
regex:Replace(text: string, replacement: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `string` | The source string. |
| `replacement` | `string` | Replacement text, which can reference captures with `$1`, `$2`. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Result with all matches replaced. |

## Example

```lua
local result = regex:Replace("hello world", "goodbye")
print(result)
```
