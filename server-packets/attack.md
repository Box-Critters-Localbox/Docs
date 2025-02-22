---
description: Documentation on the attack packet sent by the client to the server.
---

# attack

### Description

This packet is sent by the client every time the player clicks on a monster. The server then kills the monster critter, and grants the player 10 coins for defeating the monster.

> TO-DO: monsters are not thoroughly documented yet

### Parameters

| Key      | Type     | Description                   |
| -------- | -------- | ----------------------------- |
| playerId | `string` | The player ID of the monster. |
