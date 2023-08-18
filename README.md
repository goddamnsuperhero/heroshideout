# Heroes hideout
This is a mod which allows you load maps offline in single player for pavlov. It worked in 4.21 version of unreal so no idea if it works in 5.
Alot of this code isn't mine, its made by 11pan. I just rewrote some code to make it easier to change map pool for map loading and fix spawns.

NOTES you do have to play the map once offline in single player to have it unpacked for you, thenyou can play it in hero's hideout

#map loading
To look at how maps are loaded look for ucg.... > blueprints > modifiers > tool_modifier
There  is a function called doAction, there is a big section called "Load Map"
To add a new map go to  ucg.... > blueprints > modifiers > enums > MapList

you can use the unreal pak tool to unpack a file from the workshop (or mod.io's equivalent) to find the name of the map, which you will need (and its directory relative to the ucg root)

Youtube playlist of class overviews
https://www.youtube.com/playlist?list=PLsnITcSCPeMo37POY0NSJWHZ8qfH7tWHD
