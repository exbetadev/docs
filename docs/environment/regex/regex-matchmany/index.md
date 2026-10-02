# Regex:MatchMany

Finds all matches and returns their captures.

```lua
regex:MatchMany(text: string): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `string` | The string to search. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of match tables, each with `Full` and `Groups`. |

## Example

```lua
for _, match in ipairs(regex:MatchMany("1 and 2 and 3")) do
    print(match.Full)
end
```
