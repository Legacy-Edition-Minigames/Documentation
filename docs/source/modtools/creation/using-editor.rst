Using the Map Editor
====================
.. meta::
   :description lang=en: How to use the map editor when making a custom map

The ModTools Editor gives you access to multiple items. The items place objects representing map data.

..  tip::
   If you do not receive these items, type ``/function modtools:give/run``

To place objects, use your place block key (right click by default).

To remove objects, use the remove tool (more information below).

.. warning::
   Destroying blocks that were placed by an object (chests for example) will **not** remove the object. Please make sure you use the remove tool for removing objects.

.. tip::
   Installing the map editor is essential before proceeding :doc:`/modtools/creation/install-editor`

   If you only plan to create 1 map size Large+ is suggested.

   When you are finished with your map check :doc:`/modtools/uploading/post-editor`

Chests
^^^^^^

.. image:: /images/modtools/using-editor/chests.png

The Chest Items are used to create the 3 basic chests that can be found in the battle minigame.
Chests contain loot that provide players with armour, weapons, food, potions, etc.

+-----------------+---------------------------------------------------------------------------------------------------------+
| Standard Chest: | The most common chest to find on a map.                                                                 |
+-----------------+---------------------------------------------------------------------------------------------------------+
| Central Chest:  | Found at the center of the map, these should not be used anywhere else.                                 |
+-----------------+---------------------------------------------------------------------------------------------------------+
| Powerful Chest: | Rare chests containing powerful items. Don't use these often, and try to place them in risky locations. |
+-----------------+---------------------------------------------------------------------------------------------------------+

.. tip::
   These are the amount of Powerful Chests found in 4J's maps:

   **Small & Large** 2 Powerful Chests

   **Large+** 4 Powerful Chests

   It is recommended to stick near these levels of Powerful Chests for balance reasons in most scenarios.

By default, every 30 seconds 4 random chests are refilled with items.

+------------+------------------------------+
| Map size   | Spawnpoint count             |
+============+==============================+
| Small      | 8 spawnpoints of each type.  |
+------------+------------------------------+
| Large      | 8 spawnpoints of each type.  |
+------------+------------------------------+
| Large+     | 16 spawnpoints of each type. |
+------------+------------------------------+
| Remastered | 16 spawnpoints of each type. |
+------------+------------------------------+

Spawnpoints
^^^^^^^^^^^

.. image:: /images/modtools/using-editor/spawnpoints.png

Central Spawnpoint: Inital spawn locations for players, these should be placed near the Map Center and Central Chests.
Random Spawnpoint: Respawn locations for players when multiple lives are enabled or spawn locations when ``Central Spawn`` is disabled.

Here are some spawnpoint recommendations.
*If you only plan to create 1 map size Large+ is suggested.*


.. important::
   There must be at least 8 Central and 8 Random spawnpoints for a map to load properly.

   When building a Large+ map, 16 of each spawnpoint type should be used instead.


Map Center
^^^^^^^^^^

.. image:: /images/modtools/using-editor/center.png

.. tip:: 
   Once placed, it will glow when its item is held.

Not to be confused with centercoords from :doc:`/modtools/uploading/jsonschema`
The editor's map center tells the server where the players should look at round start, and where to hold players during map load.


.. important::
    This object must be placed for the map to load properly.

Positive & Negative Borders
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: /images/modtools/using-editor/borders.png

Positive Border: It is green, and should be placed at the top of the map.
Negative Border: It is red, and should be placed at the bottom of the map.

The borders should always be facing eachother when placed, they are designed to help players
align them properly.

.. tip:: 
   Once placed, both will glow when a border item is held.

.. important::
    This object must be placed for the map to load properly.

Remove Tool
^^^^^^^^^^^

.. image:: /images/modtools/using-editor/remove.png

.. tip::
   To show all objects, sneak while holding the remove tool.

The remove tool allows you to remove objects. Simply hold it and point at the object you want to remove, then click.
