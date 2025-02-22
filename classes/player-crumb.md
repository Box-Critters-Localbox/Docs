---
icon: user-group
---

# Player Crumb

### Description

A `Player Crumb` is a class that defines the condensed version of the [`Player`](player.md) type, for use of other clients so they know the bare minimum amount of information to render that player.

| Key | Type                                  | Description                                              |
| --- | ------------------------------------- | -------------------------------------------------------- |
| i   | `string`                              | The player's unique PlayFab account ID                   |
| n   | `string`                              | The player's username shown to other players             |
| c   | [`CritterID`](../enums/critter-id.md) | The ID of the critter avatar the player is wearing       |
| x   | `number`                              | The X position of the player's critter in the game world |
| y   | `number`                              | The Y position of the player's critter in the game world |
| r   | `number`                              | The rotation of the player's critter                     |
| g   | `Array<string>`                       | A list of item IDs the player is wearing                 |
| m   | `string`                              | The message the player has just recently sent            |
| e   | `string`                              | The emote the player has just recently used              |
