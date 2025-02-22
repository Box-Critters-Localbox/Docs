# joinRoom

### Description

This packet is sent by the client whenever a [World Trigger](../classes/trigger.md#world-triggers) with a `joinRoom` property is collided with, and tells the server the new room the player should be put in. First, the client is sent a reciprocated packet specifying the [`Player Crumbs`](../classes/player-crumb.md) in the room. Then, server propagates that event to all the other players in the current room telling them a certain player left, and propagates an event to the players in the new room that a certain player had joined.

### Parameters

| Key    | Type     | Description                                       |
| ------ | -------- | ------------------------------------------------- |
| roomId | `string` | The room ID of the new room to put the player in. |

