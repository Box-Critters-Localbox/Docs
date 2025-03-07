---
description: Documentation on the addEgg packet sent by the server to the client.
---

# addEgg

### Description

This packet is fired whenever the player's inventory updates, such as purchasing something from the shop, using an item code, etc.

This packet would be used in the case of a scavenger hunt, such as an egg hunt.

### Parameters

| Key      | Type     | Description                               |
| -------- | -------- | ----------------------------------------- |
| objectID | `string` | The object ID of the room object to hide. |

