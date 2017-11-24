# Unity-Sprite-Tiling

This script is for Unity2D tiling. Simply create a parent object (e.g. a cube) that you will use for collisions, etc.

Before:

After:

To use:
1) Create a parent object (e.g. a cube) that you will use for collision detection, physics, etc.
2) Create a Sprite object.
3) Attach the Sprite object to the parent as a child.
4) Add the script to the parent.

There are three modes to the script
1) Snap - Tiles will always be full tiles
2) Drag - Drag the parent object and the sprite will fill the space accordingly.
3) Tile - Use the horizontal_tiles and vertical_tiles variables to adjust tile count.