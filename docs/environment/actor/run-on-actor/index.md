# run_on_actor

Runs Luau code inside an actor's execution context.

```lua
run_on_actor(actor: Instance, code: string, args: table): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Instance` | The Actor to execute in. |
| `code` | `string` | Luau source to run. |
| `args` | `table` | Arguments passed to the code as `...`. |

## Example

```lua
local actor = getactors()[1]
run_on_actor(actor, "print(...)", { "hello" })
```

!!! note "args"
    Pass arguments through the `args` table; they arrive in the code as the varargs.
