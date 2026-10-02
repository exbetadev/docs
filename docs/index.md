# Ex:Beta Documentation

Welcome to the Ex:Beta Luau environment reference.

Ex:Beta is a Roblox script executor providing a comprehensive API for manipulating game state, inspecting runtime internals, and extending client capabilities beyond standard scripting constraints.

## Quick Start

```lua
-- load and run infinite yield
loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()

exbeta.info("test") -- custom output test

-- create test file
writefile("exmain.lua", "print('hi')")

-- read test file
local exmain = readfile("exmain.lua")
loadstring(exmain)
```

## Info

Our module has 100% sUNC and 99% myriad (100% myriad privacy)

[sUNC Test](https://sunc.rubis.app/?scrap=LnGssVPsXEKSitak&key=Eq9d00t4MhlwL2a5vH5JS4weOj4Ilqv1)

---

[Full environment](environment/index.md)
