# code

### Description

This packet is sent by the client whenever the player tries to send a message with a leading `/`. Below are tables for both available commands, and old, removed commands.

> Note: The following command tables don't include any item codes, though you can find a list on the fan-made wiki [here](https://box-critters.fandom.com/wiki/Item_Codes).

### Parameters

<table><thead><tr><th>Key</th><th width="236">Type</th><th>Description</th></tr></thead><tbody><tr><td>ticket</td><td><code>string</code></td><td>The incoming client's PlayFab account ID.</td></tr></tbody></table>

### Available Commands

<table><thead><tr><th>Command</th><th width="119" data-type="checkbox">Server-sided?</th><th>Options (&#x26; their type)</th><th>Action</th></tr></thead><tbody><tr><td>pop</td><td>true</td><td></td><td>Shows a pop-up box in the middle of the player's screen near the top with how many critters are online.</td></tr><tr><td>freeitem</td><td>true</td><td></td><td>Grants the player the latest free item, if one is available.</td></tr><tr><td>tbt</td><td>true</td><td></td><td>Grants the player the latest Throwback Thursday <em>(TBT)</em> item, if one is available.</td></tr><tr><td>darkmode</td><td>true</td><td></td><td>Grants the player the latest dark mode item, if one is available, and enables dark mode on the game page.</td></tr><tr><td>gear</td><td>true</td><td><code>list</code> item IDs</td><td>Replaces the player's gear with the specified item IDs, if the player owns them.</td></tr><tr><td>balloons</td><td>false</td><td></td><td>Toggles the visibility of "balloons" (chat messages and emotes).</td></tr><tr><td>nicknames</td><td>false</td><td></td><td>Toggles the visibility of nicknames of players.</td></tr><tr><td>join</td><td>true</td><td><code>string</code> room ID</td><td>Attempts to join the specified room ID.</td></tr><tr><td>emote</td><td>true</td><td><code>string</code> emote ID</td><td>Sends the specified emote ID.</td></tr><tr><td>treasure</td><td>false</td><td></td><td>Toggles the visibility of the current room's "treasure" (the invisible image that defines all <a href="../classes/trigger.md"><code>Trigger</code></a> colliders).</td></tr><tr><td>navmesh</td><td>false</td><td></td><td>Toggles the visibility of the current room's navigation mesh (the invisible image that defines where the player can walk).</td></tr><tr><td>zoom</td><td>false</td><td><code>number</code> magnification amount</td><td>Magnifies the game canvas by a certain amount.</td></tr><tr><td>inventory</td><td>false</td><td></td><td>Opens the player's inventory GUI.</td></tr><tr><td>ignore</td><td>true</td><td><code>string</code> nickname</td><td>Ignores a certain player - which is the equivalent to blocking them and hides them in every part of the game.</td></tr></tbody></table>

### Removed Commands

<table><thead><tr><th>Command</th><th width="127" data-type="checkbox">Server-sided?</th><th>Action</th></tr></thead><tbody><tr><td>news</td><td>false</td><td>Displays an alert with the latest in-game news.</td></tr><tr><td>now</td><td>false</td><td>Displays an alert with the server's local time.</td></tr><tr><td>beep</td><td>true</td><td>Displays an pop-up, same as when being granted an item, telling the player they are connected to the server.</td></tr><tr><td>game</td><td>false</td><td>Opens a WebGL player on the left side of the screen and runs a preview of the card game test.</td></tr><tr><td>shop</td><td>true</td><td>Opens the shop pane on the right side of the screen.</td></tr></tbody></table>
