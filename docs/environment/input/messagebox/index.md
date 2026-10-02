# messagebox

Shows a native message box.

```lua
messagebox(text: string, caption: string, flags: number): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `string` | Body text. |
| `caption` | `string` | Window title. |
| `flags` | `number` | Button layout flags. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when acknowledged. |

## Example

```lua
messagebox("Message", "Title", 0)
```
