---
description: Documentation on the message packet sent by the client to the server.
---

# message

### Description

This packet is sent by the client whenever the player sends a chat message. The packet specifies the message, and the server stores that message for a certain amount of time inside the player's [`Player Crumb`](../classes/player-crumb.md) so that if a new player enters the room while the message should still be visible, it will be visible on the new player's screen as well.

> TO-DO: mention the propagation of the M packet to the other players in the room, waiting on that page to be done first

### Parameters

| Key  | Type     | Description                          |
| ---- | -------- | ------------------------------------ |
| text | `string` | The message the player wants to say. |

