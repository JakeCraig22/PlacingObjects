# PlacingObjects

The idea of this was to be able to script something to pick up an item and then be able to place said item in some designated area

Note that there are multiple of these scripts for each object which is why each scripts references one item. This was my first thing I made in over a year on lua, looking back they all could've gone in one script and been put into a list which is what I did in my future codes.

ClickToPutInInventory.lua - On proximity prompt, the item being prompted will be placed into the users backpack and the physical item in workspace will be destroyed

placingObject.lua - Places the object to a designated area, other functions:
- Checks user inventory for a specific item
- Checks if user is a player and takes the item out of the users bag and takes a clone item from the game server storage and puts it on the placeHere object.

Demo: https://youtu.be/-V9pNDIEAsI
