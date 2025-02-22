---
icon: user
description: A player object represents the local player.
---

# Player

### Description

The `Player` type represents the local player. On login, this is sent to the client so it knows everything about the local player, and how to render their critter. When this object is sent to other clients, it is first compressed into a `PlayerCrumb`, which is heavily condensed version of the standard `Player` type.

| Key       | Type            | Description                                                                                                                                       |
| --------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| playerId  | `string`        | The player's unique PlayFab account ID                                                                                                            |
| nickname  | `string`        | The player's username shown to other players                                                                                                      |
| critterId | `CritterID`     | The ID of the critter avatar the player is wearing                                                                                                |
| ignore    | `Array<number>` | A list of player(s) the player wants to hide in-game, similar to a block list                                                                     |
| friends   | `Array<number>` | A list of player(s) the player wants to befriend, this was never implemented in-game unless you sent a packet via your browser's DevTools console |
| inventory | `Array<string>` | A list of item IDs the player owns                                                                                                                |
| gear      | `Array<string>` | A list of item IDs the player is wearing                                                                                                          |
| eggs      | `Array<string>` | A list of room object IDs that the player has collected, this would be used in the case of a scavenger hunt such as an egg hunt                   |
| coins     | `number`        | The balance of coins the player has                                                                                                               |
| isMember  | `boolean`       | N/A                                                                                                                                               |
| isGuest   | `boolean`       | N/A                                                                                                                                               |
| isTeam    | `boolean`       | Specifies whether or not the player is apart of the Box Critter's team                                                                            |
| x         | `number`        | The X position of the player's critter in the game world                                                                                          |
| y         | `number`        | The Y position of the player's critter in the game world                                                                                          |
| rotation  | `number`        | The rotation of the player's critter                                                                                                              |
| mutes     | `Array<N/A>`    | N/A                                                                                                                                               |
