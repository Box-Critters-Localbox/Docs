---
icon: info
description: >-
  Files which contain information on stuff like all of the critters, rooms, and
  mascots in Box Critters.
---

# Base Files

### Description

On page load, the game would load several "base" `JSON` files. These files would contain information on stuff like all of the critters, rooms, and mascots in the game. If you are into Club Penguin private server development, these are similar to the `JSONP` files often loaded by Flash private servers.

### Manifest

Some versions of Box Critter's client used a manifest `JSON` file rather than having the URLs inline in the Javascript. Below is the manifest Localbox uses, which is a slightly modified version of the official one:

```json
{
	"manifest": [
		{
			"id": "items",
			"src": "../base/items.json"
		},
		{
			"id": "shops",
			"src": "../base/shops.json"
		},
		{
			"id": "critters",
			"name": "hamster",
			"src": "../media/critters/hamster/data.json"
		},
		{
			"id": "critters",
			"name": "beaver",
			"src": "../media/critters/beaver/data.json"
		},
		{
			"id": "critters",
			"name": "snail",
			"src": "../media/critters/snail/data.json"
		},
		{
			"id": "critters",
			"name": "raccoon",
			"src": "../media/critters/raccoon/data.json"
		},
		{
			"id": "critters",
			"name": "lizard",
			"src": "../media/critters/lizard/data.json"
		},
		{
			"id": "critters",
			"name": "penguin",
			"src": "../media/critters/penguin/data.json"
		},
		{
			"id": "critters",
			"name": "snow_greeter",
			"src": "../media/critters/snow_greeter/data.json"
		},
		{
			"id": "critters",
			"name": "snowkeeper",
			"src": "../media/critters/snowkeeper/data.json"
		},
		{
			"id": "critters",
			"name": "snowgirl",
			"src": "../media/critters/snowgirl/data.json"
		},
		{
			"id": "critters",
			"name": "snow_patrol",
			"src": "../media/critters/snow_patrol/data.json"
		},
		{
			"id": "critters",
			"name": "snowgrandma",
			"src": "../media/critters/snowgrandma/data.json"
		},
		{
			"id": "critters",
			"name": "huggable",
			"src": "../media/critters/huggable/data.json"
		},
		{
			"id": "emotes",
			"src": "../media/emotes/sprites.json",
			"type": "spritesheet"
		},
		{
			"id": "assets",
			"src": "../media/assets/sprites.json",
			"type": "spritesheet"
		},
		{
			"id": "shop",
			"src": "../media/shops/sprites.json",
			"type": "spritesheet"
		},
		{
			"id": "symbols",
			"src": "../media/symbols/sprites.json",
			"type": "spritesheet"
		},
		{
			"id": "effects",
			"src": "../media/effects/sprites.json",
			"type": "spritesheet"
		}
	]
}
```

> TO-DO: upload the latest known archived version of each known base file to a public GitHub repository and then link the files here

