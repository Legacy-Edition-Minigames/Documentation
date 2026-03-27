Map requirements
================
.. meta::
   :description lang=en: Requirements for a custom map to be functional

.. tip::
   If you only plan to create 1 map size Large+ is suggested.

Json Arguments
^^^^^^^^^^^^^^
**All** elements of the lebmod.json must be in compliance with the :doc:`/modtools/uploading/jsonschema`
If a hasmaptype value is set to true, there **must** be a folder and map files for that map type,
otherwise the map will fail to load.

Map size
^^^^^^^^
The playable area of the map, **must** be within a 10 chunk render distance from the map center.
This includes the border entities, which are at the edges of the playable area.
If you need help fulfilling this requirement please follow the trimming guide found in :doc:`/modtools/uploading/post-editor`

Minecraft version
^^^^^^^^^^^^^^^^^
The world file for the mod must be for ``1.20.4`` in order for the server to
load it properly. This is because the server runs on ``1.20.4``.

Required Chests
^^^^^^^^^^^^^^^
There are no set minimums or maximums for Chests; 
however there are some recommendations for center and powerful chests.

+-----------+---------------+-----------------+
| Map Size  | Center Chests | Powerful Chests |
+===========+===============+=================+
| Small     | 5             | 2               |
+-----------+---------------+-----------------+
| Large     | 5             | 2               |
+-----------+---------------+-----------------+
| Large+    | 9             | 4               |
+-----------+---------------+-----------------+


Required Spawnpoints
^^^^^^^^^^^^^^^^^^^^
There must be at least 8 Central and 8 Random spawnpoints for a map to load properly.
When building a Large+ map, 16 of each spawnpoint type should be used instead.

Here are some spawnpoint recommendations.
*If you only plan to create 1 map size Large+ is suggested.*

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



Required Map Center
^^^^^^^^^^^^^^^^^^^
There should be 1 map center in a map in order for it to load properly

Required Borders
^^^^^^^^^^^^^^^^
.. attention::
    The borders must stay within the 10 chunk render distance of the map center, or else it will fail to load.

There must be a positive and negative border, the positive border **must** be above the negative border. Otherwise, the map will not function properly

The borders are used to define where the in-game world border should be that prevents players from going outside of the map.
