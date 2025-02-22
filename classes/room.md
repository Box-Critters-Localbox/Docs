---
icon: house
---

# Room

A `Room` is a class which is pretty self-explanatory. Each room is layered in several different assets, including a background (can be an image or a video), foreground, props sprite-sheet, layout `JSON`, music, etc.

The following table shows the structure of room data. Each room's data was specified in the [rooms base file](../basics/base-files.md) which is fetched on page load.



| Key         | Type                                     | Description                                                                                                                                  |
| ----------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| roomId      | `string`                                 | The internal name of the room, usually just a lowercase no-space version of the display name. (eg. `tavern`)                                 |
| name        | `string`                                 | The display name of the room, pretty self-explanatory.                                                                                       |
| width       | `number`                                 | The width of the room.                                                                                                                       |
| height      | `number`                                 | The height of the room.                                                                                                                      |
| startX      | `number`                                 | The X position each player starts at when they join the room.                                                                                |
| startY      | `number`                                 | The Y position each player starts at when they join the room.                                                                                |
| startR      | `number`                                 | The rotation each player starts at when they join the room.                                                                                  |
| media       | `Record<string, string>` (defined below) | The URLs of different assets the room requires.                                                                                              |
| layout      | `string`                                 | The URL of the layout `JSON` file. The layout file determines the position, width, height, registration point, etc of each prop in the room. |
| triggers    | `Array<`[`Trigger`](trigger.md)`>`       | The triggers in the room. For more information on triggers, go to the [Trigger](trigger.md) class documentation.                             |
| spriteSheet | `string`                                 | The URL of the sprite-sheet `JSON` file.                                                                                                     |
| extra       | TO-DO (requires another page)            | TO-DO                                                                                                                                        |

### Room Media

The following table describes the structure of the `media` property of the above table, separated so the documentation is clearer.

| Key           | Type     | Description                                                                                                        |
| ------------- | -------- | ------------------------------------------------------------------------------------------------------------------ |
| background    | `string` | The URL of the background image.                                                                                   |
| foreground`?` | `string` | The URL of the foreground image.                                                                                   |
| treasure      | `string` | The URL of the treasure image which defines the colliders for the room's triggers.                                 |
| navMesh       | `string` | The URL of the navigation mesh which determines where the player can walk in the room.                             |
| music`?`      | `string` | The URL of the music in the room, if any.                                                                          |
| video`?`      | `string` | The URL of the video background of the room, if there is one. This was only used for the redesigned _Bridge_ room. |
