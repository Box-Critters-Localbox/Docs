---
description: Documentation on the login packet sent by the server to the client.
---

# login

### Description

This packet is a reciprocated packet from the server, sent whenever the player clicks the login button on the homepage.

### Parameters

| Key    | Type                             | Description                                           |
| ------ | -------------------------------- | ----------------------------------------------------- |
| player | [`Player`](../classes/player.md) | Everything the client needs to know about the player. |

### Localbox Parameters

Localbox has a slightly modified version of this packet. This is so that I can have a constant on the server defining the spawnRoom, and I don't have to update it on the client every time.

| Key       | Type                             | Description                                           |
| --------- | -------------------------------- | ----------------------------------------------------- |
| player    | [`Player`](../classes/player.md) | Everything the client needs to know about the player. |
| spawnRoom | `string`                         | The room to spawn the player in on login.             |

