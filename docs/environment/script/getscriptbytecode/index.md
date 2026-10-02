# getscriptbytecode

Returns the compiled bytecode of a script.

```lua
getscriptbytecode(script: Instance): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Instance` | A LocalScript, ModuleScript or Script. |

## Returns

| Type | Description |
| --- | --- |
| `string` | The bytecode, or an empty string when unavailable. |

## Example

```lua
local bytecode = getscriptbytecode(script)
print(#bytecode)
```
