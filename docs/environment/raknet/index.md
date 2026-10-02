---
icon: lucide/network
---

---
tags:
  - Raknet
---

# Raknet

Build and inspect RakNet packets.

| Function | Description |
| --- | --- |
| [`raknet.BitStream`](raknet-bitstream/index.md) | Creates an empty bit stream for writing a packet. |
| [`Write`](write/index.md) | Writes raw bytes into the stream. |
| [`WriteString`](writestring/index.md) | Writes a length-prefixed string. |
| [`WriteU8`](writeu8/index.md) | Writes an unsigned 8-bit value. |
| [`WriteU16`](writeu16/index.md) | Writes an unsigned 16-bit value. |
| [`WriteU32`](writeu32/index.md) | Writes an unsigned 32-bit value. |
| [`WriteFloat`](writefloat/index.md) | Writes a 32-bit float. |
| [`WriteDouble`](writedouble/index.md) | Writes a 64-bit double. |
| [`Clear`](clear/index.md) | Discards all buffered data. |
| [`GetLength`](getlength/index.md) | Returns the buffered length in bytes. |
| [`ToString`](tostring/index.md) | Returns the buffer contents as a string. |
| [`Send`](send/index.md) | Sends the stream as a network packet. |
| [`raknet.send`](raknet-send/index.md) | Sends a prepared bit stream. |
| [`raknet.desync`](raknet-desync/index.md) | Toggles the desync state, which alters outbound packet delivery. |
| [`raknet.capturepaused`](raknet-capturepaused/index.md) | Pauses packet capture so the log stops growing. |
| [`raknet.add_send_hook`](raknet-add-send-hook/index.md) | Registers a callback invoked for every outbound packet. |
| [`raknet.remove_send_hook`](raknet-remove-send-hook/index.md) | Removes a previously added send hook. |
| [`raknet.add_receive_hook`](raknet-add-receive-hook/index.md) | Registers a callback invoked for every inbound packet. |
| [`raknet.remove_receive_hook`](raknet-remove-receive-hook/index.md) | Removes a previously added receive hook. |
| [`raknet.getpacketlog`](raknet-getpacketlog/index.md) | Returns the captured packet log. |
| [`raknet.clearpacketlog`](raknet-clearpacketlog/index.md) | Clears the captured packet log. |
