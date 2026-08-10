# MShockXotto+ style guide

MShockXotto+ was originally the mashup of the MShock and the Xotto tileset, both of which were already build on a few other tilesets. This means that MSX never had a strong style guide.
And it still has not, the present style guide will list a few rules to follow but since MSX is a patchwork of different styles there's a lot of wriggle around the guide.
The main thing that we want to keep from the previous tilesets is the anime/cartoon style of the monsters and characters, and the main thing we're moving away from is the random noise over sprites.

- Cartoon style, make your sprite recognisable.
- Clean texture without random noise
- Keep the colour count per material (bone, meat, cotton, wood, metal etc...) low, around 3-4 per material.

## Monsters

![monsters](image/monsters.png)

- Black outline RGBA(0,0,0,255)
- Do not draw a shadow under the monster. Shadows are applied via the "bg" field in the accompanying json file.

## Items

![items](image/items.png)

- Black outline RGBA(0,0,0,255)
- Items should be roughly scaled to the character, meaning that small object like pens and box cutter should be 20x20 and big items like disconnected oven should be 32x32.
- We may sometimes need to magnify items to make them legible, but in general scaling them is preferable.
## Furniture

![furnitures](image/furnitures.png)

- Outline using a less-saturated, darker color taken from the sprite's palette.

## Terrain

![terrain](image/terrain.png)

- No outline required
- Terrain should fill their canvas as the game doesn't display anything behind them. Transparency will appear black in game, and may cause unforeseen visual errors.
