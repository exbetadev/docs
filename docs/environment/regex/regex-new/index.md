# Regex.new

Compiles a regular expression.

```lua
Regex.new(pattern: string, flags: string?): Regex
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `string` | ECMAScript regex pattern. |
| `flags` | `string?` | Optional flags: `i` for case-insensitive, `m` for multiline. |

## Returns

| Type | Description |
| --- | --- |
| `Regex` | Compiled regex object. |

## Example

```lua
local regex = Regex.new("\\d+", "i")
```
