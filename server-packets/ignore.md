# ignore

### Description

This packet is sent by the client every time the player attempts to ignore another player. The server then adds that player to the ignore list of the "origin player". Ignoring a player is similar to blocking a player on other platforms, and will hide the player's chats, emotes, and their critter.

### Parameters

| Key      | Type     | Description                                                               |
| -------- | -------- | ------------------------------------------------------------------------- |
| playerId | `string` | The player ID of the other player the "origin player" is trying to block. |
