---
description: Documentation on the buyItem packet sent by the client to the server.
---

# buyItem

### Description

This packet is sent by the client every time the attempts to buy an item in the shop GUI. If the player has enough coins to purchase the item, the coins are deducted and then the item is granted to the player.

> TO-DO: mention the 2 returning packets, buyItem and updateCoins, waiting on those pages to be done first

### Parameters

| Key    | Type     | Description                                          |
| ------ | -------- | ---------------------------------------------------- |
| itemId | `string` | The item ID of the item the player is trying to buy. |
