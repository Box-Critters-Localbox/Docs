# G (gear update)

### Description

This packet is fired to all other clients in the room when a player updates their gear.

### Parameters

| Key | Type            | Description                                  |
| --- | --------------- | -------------------------------------------- |
| i   | `string`        | The ID of the player who updated their gear. |
| g   | `Array<string>` | A list of item IDs the player is wearing.    |

