# gethui

Returns the hidden UI container for executor GUIs.

```lua
gethui(): Instance
```

## Returns

| Type | Description |
| --- | --- |
| `Instance` | A ScreenGui under CoreGui that is invisible to the game. |

## Example

```lua
local container = gethui()
local gui = Instance.new("ScreenGui")
gui.Parent = container
```
