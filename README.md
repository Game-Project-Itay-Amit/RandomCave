# RandomCave

Itch.io: https://amitay2022.itch.io/randomcave

## Scripts:

### [CaveGenerator](https://github.com/Game-Project-Itay-Amit/RandomCave/blob/main/Assets/Scripts/CaveGenerator.cs):

We split in the function RandomizeMap() the random generator, from two to three - the number of tiles in the game.
Plus in SmoothMap() we added another if statement for the third tile.
Finally in GetSurroundingWallCount() we added another field that represents the type of tile surrounding a specific tile.

### [TilemapCaveGenerator](https://github.com/Game-Project-Itay-Amit/RandomCave/blob/main/Assets/Scripts/TilemapCaveGenerator.cs):

In GenerateAndDisplayTexture() we added another if statement for the third tile we declared as rockTile, which is defined by the user.

