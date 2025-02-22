---
description: Documentation on the emote packet sent by the client to the server.
---

# emote

### Description

This packet is sent by the client whenever the player sends an emote. The packet specifies the emote's ID, and the server stores that specific ID for a certain amount of time inside the player's [`Player Crumb`](../classes/player-crumb.md) so that if a new player enters the room while the emote should still be visible, it will be visible on the new player's screen as well.

> TO-DO: mention the propagation of the E packet to the other players in the room, waiting on that page to be done first

### Parameters

| Key  | Type     | Description                          |
| ---- | -------- | ------------------------------------ |
| text | `string` | The message the player wants to say. |

