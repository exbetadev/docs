# ExBeta Documentation

**ExBeta** is a Roblox script executor providing low-level Luau API access for developers.

## Quick Start

```lua
print(identifyexecutor())          -- ExBeta, 1.1.5

local body = HttpGet("https://example.com/")
writefile("out.txt", body)

local line = Drawing.new("Line")
line.From = Vector2.new(100, 100)
line.To   = Vector2.new(300, 200)
line.Visible = true

local old
old = hookfunction(game.IsLoaded, function(...)
    print("hooked")
    return old(...)
end)
```

## Environment

- **Workspace**: `%LOCALAPPDATA%/ExBeta/Workspace` — root directory for filesystem functions
- **AutoExecute**: `%LOCALAPPDATA%/ExBeta/AutoExecute` — scripts run on game load
- **getgenv()** — persistent environment shared across scripts

## Library Overview

| Category | Functions | Description |
| --- | --- | --- |
| **Closures** | 12 | loadstring, hookfunction, newcclosure, clonefunction, checkcaller |
| **Metatable** | 11 | getrawmetatable, hookmetamethod, setidentity, setreadonly |
| **Debug** | 11 | getupvalue, getconstants, getproto, getstack, getinfo |
| **Http** | 4 | HttpGet, HttpPost, request (async) |
| **WebSocket** | 5 | WebSocket.connect, Send, OnMessage |
| **Raknet** | 20 | BitStream, send/receive hooks, packet logging |
| **Filesystem** | 12 | readfile, writefile, listfiles, makefolder, getcustomasset |
| **Crypt** | 7 | base64, hash (md5/sha1/sha256/sha384/sha512), AES encrypt/decrypt |
| **Regex** | 4 | Regex.new, Match, Replace, Escape |
| **Bit** | 10 | band, bor, bxor, lshift, rshift, arshift, tohex |
| **Instance** | 3 | gethui, getinstances, getnilinstances |
| **Cache** | 6 | cache.invalidate, cache.replace, cloneref, compareinstances |
| **Reflection** | 9 | isscriptable, setscriptable, gethiddenproperty, getcallbackvalue |
| **Script** | 11 | getscripts, getrunningscripts, getscriptbytecode, getsenv, getgc |
| **Signals** | 14 | getconnections, firesignal, fireclickdetector, firetouchinterest |
| **Drawing** | 15 | Drawing.new (Line, Circle, Square, Quad, Triangle, Image, Text) |
| **Input** | 15 | keypress, mouse1click, mousemoveabs, setclipboard, messagebox |
| **Actor** | 5 | getactors, run_on_actor, create_comm_channel, isparallel |
| **Misc** | 11 | identifyexecutor, getgenv, getrenv, setfpscap, queueonteleport |
| **Oth** | 8 | oth.hook, oth.unhook, oth.is_hooked, oth.get_root_callback |

**208 functions** across **20 categories**.

---

Browse the full API reference in the **Environment** section.
