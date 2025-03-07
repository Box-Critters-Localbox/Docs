---
description: Documentation on the pop packet sent by the server to the client.
---

# pop

### Description

This packet is a reciprocated packet from the server, sent whenever the player sends the `/pop` [code](../server-packets/code.md).

### Parameters

| Key      | Type     | Description                    |
| -------- | -------- | ------------------------------ |
| critters | `number` | The number of critters online. |
