---
icon: lucide/radio
---

---
tags:
  - Signals
---

# Signals

Inspect and fire connections and game signals.

| Function | Description |
| --- | --- |
| [`getconnections`](getconnections/index.md) | Returns all connections attached to a signal. |
| [`getconnection`](getconnection/index.md) | Returns a single connection by index. |
| [`firesignal`](firesignal/index.md) | Fires all connections attached to a signal. |
| [`defersignal`](defersignal/index.md) | Fires a signal at the end of the current scheduler step. |
| [`replicatesignal`](replicatesignal/index.md) | Fires a signal and replicates the result to the server. |
| [`fireproximityprompt`](fireproximityprompt/index.md) | Triggers a ProximityPrompt as though it were used. |
| [`fireclickdetector`](fireclickdetector/index.md) | Triggers a ClickDetector as though it were clicked. |
| [`firetouchinterest`](firetouchinterest/index.md) | Simulates a touch between two parts. |
| [`setproximitypromptduration`](setproximitypromptduration/index.md) | Sets the hold duration of a ProximityPrompt. |
| [`getproximitypromptduration`](getproximitypromptduration/index.md) | Returns the hold duration of a ProximityPrompt. |
| [`getsignalwhitelist`](getsignalwhitelist/index.md) | Returns the allowlist of signals that may be replicated. |
| [`cansignalreplicate`](cansignalreplicate/index.md) | Checks whether a signal can be replicated to the server. |
| [`getsignalargumentsinfo`](getsignalargumentsinfo/index.md) | Returns argument metadata for a signal. |
| [`getsignalarguments`](getsignalarguments/index.md) | Returns the argument list of a signal. |
| [`getrendersteppedlist`](getrendersteppedlist/index.md) | Returns the current list of RenderStepped connections. |
