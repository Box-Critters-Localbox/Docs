---
description: Documentation on the moveTo packet sent by the client to the server.
---

# moveTo

### Description

This packet is sent by the client whenever the player clicks somewhere within the navigation mesh of a [`Room`](../classes/room.md). The packet specifies the X and Y of the new location, and then the server propagates that to all the other players in the room. The direction is not included in the packet, because it is calculated by the server.

### Parameters

| Key | Type     | Description                              |
| --- | -------- | ---------------------------------------- |
| x   | `number` | The X coordinate of the target position. |
| y   | `number` | The Y coordinate of the target position. |

