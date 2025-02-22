---
description: Documentation on the login packet sent by the client to the server.
---

# login

### Description

This packet is sent by the client on log-in, and tells the server their PlayFab account ID. The server then grabs the player's data, generates a [`Player Crumb`](../classes/player-crumb.md) , and sends it to the other players inside the spawn room.

This packet can only be fired once per socket connection.

### Parameters

| Key    | Type     | Description                               |
| ------ | -------- | ----------------------------------------- |
| ticket | `string` | The incoming client's PlayFab account ID. |
