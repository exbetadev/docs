# cache.iscached

Checks whether an instance is in the cache.

```lua
cache.iscached(instance: Instance): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The instance to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when cached. |

## Example

```lua
print(cache.iscached(workspace)) -- true
```
