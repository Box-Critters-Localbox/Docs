---
description: Documentation on the X (player moved) packet sent by the server to the client.
---

# X (player moved)

### Description

This packet is fired to all clients in the room when a player leaves the room.

### Parameters

| Key | Type     | Description                                                                 |
| --- | -------- | --------------------------------------------------------------------------- |
| i   | `string` | The ID of the player who moved.                                             |
| x   | `number` | The X coordinate of the player's new position.                              |
| y   | `number` | The Y coordinate of the player's new position.                              |
| r   | `number` | The direction the player would result in when moving to their new position. |

