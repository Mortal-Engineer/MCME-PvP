MCME-PVP
===========

## PVP for MCME
This project is once again in development!

### Bug fixes
* Team Conquest - apparently it's bugged, but I don't know what specifically

### To be implemented
* /pvp help - guide for setting up maps and starting games
* Keep track of sessions for players so they can be reassigned to the same team on rejoin
* /pvp assign \<player> \<team> to assign a player to a certain team in a running game
* pipe smoke texture
* xxxEvent point to get events on maps (look wether to hardcode or not)

### Code improvements
* Simplify the command files so they're easier to read
* Tests? This might be a bit ambitious

### New Features
* UI for map creation and editing (with showing spawns)
* Teleportation to maps
* Brigadier command parser
* An actual queue for PVP
* An updated permission system
* A death run gamemode

Needed commands for wrapper:

Shell: mv plugins\update\MCME-Events-0.1.jar plugins\MCME-Events-0.1.jar

MSDOS: MOVE /y plugins\update\MCME-Events-0.1.jar plugins\MCME-Events-0.1.jar