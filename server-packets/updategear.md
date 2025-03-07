---
description: Documentation on the updateGear packet sent by the client to the server.
---

# updateGear

### Description

This packet is sent by the client every time the inventory GUI is closed, no matter if there is a change in gear or not. The server then goes through the list of item IDs sent in the packet, and equips them if the player owns them. Then, the server propagates any changes to the other players in the room in the form of a [G packet](../g-gear-update.md).

### Parameters

| Key  | Type            | Description                                                 |
| ---- | --------------- | ----------------------------------------------------------- |
| gear | `Array<string>` | The complete list of item IDs the player is trying to wear. |
