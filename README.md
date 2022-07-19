# Map Editor V3 Building Data Migration

## Purpose
### This is a tool for users who have been using the mapeditor v3 and cannot remove buildings, but want to keep all their self-made categories and its' contents.
### **If** you **can** remove buildings with the map editor, then you **do not** need this script.

By using this tool instead of replacing your mapedit.db with a new one, you will keep all of your categories and their items intact, and still retrieve all of the building data required for removing buildings.


## Credits:
* **Pottus** - All GTA SA Objects Array.

## How To:
* Download everything required, download links can be found further down.

### How to Compile:
* Extract ```mapedit_buildmigrator.pwn``` to your ```filterscripts``` folder.
* Compile the code using pawno.
* If the compilation was successful you should have the file ```mapedit_buildmigrator.amx``` in your filterscripts folder now.
### OR
* Extract ```mapedit_buildmigrator.amx``` to your ```filterscripts``` folder.

### How to Load:
* Add ```mapedit_buildmigrator``` to your ```server.cfg``` filterscripts line, then start your server.
### OR
* Type ```loadfs mapedit_buildmigrator``` in the server console window once opened, then press enter.
### After loading:
Wait until the console messages stops feeding the please wait message. 
It should stop at something like this: ```migrating building data... please wait! 100% finished```
### Done!
You may now unload ```mapedit_buildmigrator``` and remove it if you wish.

## Download:
* Building Migrator for Map Editor V3
  * [GitHub Download](https://github.com/fusez/Map-Editor-V3-BuildMigrator/archive/refs/heads/master.zip)
  * [GitHub Page](https://github.com/fusez/Map-Editor-V3-BuildMigrator)
* Map Editor V3 (Required)
  * [GitHub Download](https://github.com/fusez/Map-Editor-V3/archive/master.zip)
  * [GitHub Page](https://github.com/fusez/Map-Editor-V3)
