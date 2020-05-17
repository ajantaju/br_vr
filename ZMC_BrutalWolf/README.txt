Basic VRweapon for GZDoom.

File contents:

Credit.txt: Credits go here, so people know who has done what models/sounds/textures etc...

Decorate.txt: Tells the game what files to load. Here we add more weapon logic files to load. https://zdoom.org/wiki/DECORATE

Weapon01.txt: Weapon logic example. Copy and rename to start new weapon. https://zdoom.org/wiki/Creating_new_weapons

Modeldef.TEMP.def: Tells the game what (dummy)sprites to replace with what 3d models frames. Copy and rename for a new weapon. https://zdoom.org/wiki/MODELDEF
-Modeldef.TEMP.def: Backup file.

Player.txt: Player defination file. If a custom player is needed. https://zdoom.org/wiki/Classes:PlayerPawn // https://zdoom.org/wiki/Creating_new_player_classes

README.txt: This file.

Folder contents:

Sprites/ 
	RTEMA0.PNG: Pickup sprite for our custom weapon
	TEMPA0.PNG: Empty dummy sprite that we use in the weapon logic file to define animations. Copy and rename for a new weapon.

Models/TEMP/
	TEMP.MD3: Our exported 3d model (Example is Index controller model.)
	TEMP.PNG: Texture for the model.
