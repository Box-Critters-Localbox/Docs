---
description: Documentation on the E (emote sent) packet sent by the server to the client.
---

# E (emote sent)

### Description

This packet is fired to all clients in the room when a player sends an emote.

### Parameters

| Key | Type     | Description                              |
| --- | -------- | ---------------------------------------- |
| i   | `string` | The ID of the player who sent a message. |
| e   | `string` | The ID of the emote the player sent.     |

