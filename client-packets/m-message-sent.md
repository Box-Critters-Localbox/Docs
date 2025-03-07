---
description: Documentation on the M (message sent) packet sent by the server to the client.
---

# M (message sent)

### Description

This packet is fired to all clients in the room when a player sends a message.

### Parameters

| Key | Type     | Description                              |
| --- | -------- | ---------------------------------------- |
| i   | `string` | The ID of the player who sent a message. |
| m   | `string` | The text of the player's message.        |

