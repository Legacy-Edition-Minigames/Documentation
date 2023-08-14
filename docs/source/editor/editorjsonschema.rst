Json Schema
===========================
.. meta::
   :description lang=en: All about lebmod.json


What is lebmod.json ?
-----------
Lebmod.json tells the installer everything it knows about your map.
without it, the installer wouldn't know it exists.
+-------------------------+--------------------------------------------------------------------------------------------+
| Value name              | Value function                                                                             |
+=========================+============================================================================================+
| name                    | This is the name that will appear to users when they go to select the map.                 |
+-------------------------+--------------------------------------------------------------------------------------------+
| description             | What is the map about? Lore? The description that appears when being voted for.            |
+-------------------------+--------------------------------------------------------------------------------------------+
| authors                 | The credits for the map, and anyone else you feel like.                                    |
+-------------------------+--------------------------------------------------------------------------------------------+
| version                 | This value will will show which version of the map is being used.                          |
+-------------------------+--------------------------------------------------------------------------------------------+
| id                      | The internal map name, must be unique to avoid conflicts with other maps.                  |
+-------------------------+--------------------------------------------------------------------------------------------+
| type                    | **Unused** This is a value is saved for future versions of the Map Editor.                 |
+-------------------------+--------------------------------------------------------------------------------------------+
| pack                    | Resource pack to be loaded by client. :doc:`/editor/resourcepacks`                         |
+-------------------------+--------------------------------------------------------------------------------------------+
| hassmall                | Does this map have a version for small map sizes? If yes it will look for the small folder.|
+-------------------------+--------------------------------------------------------------------------------------------+
| haslarge                | Does this map have a version for large map sizes? If yes it will look for the large folder.|
+-------------------------+--------------------------------------------------------------------------------------------+
| haslargeplus            | Does this map have a largeplus map size? If yes it will look for the largeplus folder.     |
+-------------------------+--------------------------------------------------------------------------------------------+
| hasremastered           | Does this map have a remastered map? If yes it will look for the remastered folder.        |
+-------------------------+--------------------------------------------------------------------------------------------+
| centercoords_small      | The coordinates of the map center tool for the small map size.                             |
+-------------------------+--------------------------------------------------------------------------------------------+
| centercoords_large      | The coordinates of the map center tool for the large map size.                             |
+-------------------------+--------------------------------------------------------------------------------------------+
| centercoords_largeplus  | The coordinates of the map center tool for the largeplus map size.                         |
+-------------------------+--------------------------------------------------------------------------------------------+
| centercoords_remastered | The coordinates of the map center tool for the remastered version of the map.              |
+-------------------------+--------------------------------------------------------------------------------------------+