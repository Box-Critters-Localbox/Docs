---
description: Documentation on the trigger packet sent by the client to the server.
---

# trigger

### Description

This packet is sent by the client every time any type of [`Trigger`](../classes/trigger.md) is collided with. The server then gets the HEX color of the pixel the player is standing on and if it matches any trigger in the current room's triggers array, it will execute whatever functionality that trigger has specified.
