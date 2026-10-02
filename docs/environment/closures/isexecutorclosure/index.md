# isexecutorclosure

Checks whether a function originates from the executor.

```lua
isexecutorclosure(fn: any): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `any` | The function to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the function was created by ExBeta. |

## Aliases

- `checkclosure`
- `isourclosure`
- `isexecutorfunction`

## Example

```lua
local mine = loadstring("return function() end")()
print(isexecutorclosure(mine))         -- true
print(isexecutorclosure(game.HttpGet)) -- false
```
