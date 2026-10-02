# Regex.Escape

Escapes special regex characters so the string matches literally.

```lua
Regex.Escape(text: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `string` | The string to escape. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Escaped pattern. |

## Example

```lua
local literal = Regex.Escape("a.b")
print(literal) -- a\.b
```
