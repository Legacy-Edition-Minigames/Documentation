Using the Map Editor
=========================

The ModTools Editor gives you access to multiple items. The items place objects representing map data.

To place objects, use your place block key (right click by default).

To remove objects, use the edit tool (more information below).

.. warning::
   Destroying blocks that were placed by an object (chests for example) will **not** remove the object. Please make sure you use the edit tool for removing objects.

.. attention::
   These descriptions could be improved! Any suggestions would be appreciated

Chests
^^^^^^

.. image:: /images/modtools/using-editor/chests.png

Chests contain loot that provide players with armor, weapons, food, potions, etc.

By default, every 30 seconds 4 random chests are refilled with items.

Standard Chest: The most common chest to find on a map.

Central Chest: Found at the center of the map, these should not be used anywhere else.

Powerful Chest: Rare chests containing powerful items. Don't use these often, and try to place them in risky locations.

.. tip::
   These are the amount of Powerful Chests found in 4J's maps:

   **Small & Large** 2 Powerful Chests

   **Large+** 4 Powerful Chests

   It is recommended to stick near these levels of Powerful Chests for balance reasons in most scenarios.

Spawnpoints
^^^^^^^^^^^

.. image:: /images/modtools/using-editor/spawnpoints.png

Central Spawnpoint: Inital spawn locations for players, these should be placed near the Map Center and Central Chests.

Random Spawnpoint: Respawn locations for players when multiple lives are enabled.

.. note::
    Keep in mind if the host disables the ``Central Spawn`` option in host settings Random Spawnpoints will be used as the inital spawn locations.

.. important::
   There must be at least 8 Central and 8 Random spawnpoints for a map to load properly.

   When building a Large+ map, 16 of each spawnpoint type should be used instead.


Map Center
^^^^^^^^^^

.. image:: /images/modtools/using-editor/center.png

The map center tells the server where the players should look at round start, and where to keep everyone during map load.

.. important::
    This object must be placed for the map to load properly.

Positive & Negative Borders
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. error::
    This object is currently in the process of being reworked, documentation will be made once this is completed.

.. important::
    This object must be placed for the map to load properly.

Edit Tool
^^^^^^^^^

.. error::
    This object is currently in the process of being reworked, documentation will be made once this is completed.
