Creating the map directory
===========================
.. meta::
   :description lang=en: How to set up the folder your map data sits in when making a custom map

What is the map directory?
--------------------------

The map directory is where all the data required to compile a map is stored, all the map sizes, dimension data, and metadata.

.. attention::
   If you are planning to submit your map to the server, ignore this guide. Use the :doc:`/modtools/uploading/github` instead

Adding world data
-----------------

1. Download the `template <https://github.com/Legacy-Edition-Minigames/Example-LEM-Mod>`_


  * Click on the ``<> Code`` button
  * Click ``Download ZIP`` and save the file
  * Extract the folder, and change its name to your map's name

2. Exit the world in Minecraft, and locate your world's folder

   * Before closing the world, go to the center of the map and press F3 and make note note of your coordinates and save them for later.
   * To get to the folder, go to ``Singleplayer`` -> ``Edit`` -> ``Open world folder``

.. image:: /images/modtools/install-editor/edit-button.png

.. image:: /images/modtools/install-editor/openworldfolder-button.png

3. Copy the world data to your map directory

   * Go to ``src/world/``
   * Remove the contents of the ``largeplus`` before copying
   * Create a folder with the name of the map type you're using and copy your world data into it

   .. note::
    There are 4 possible map types, ``small``, ``large``, ``largeplus``, and ``remastered``

    More information can be found on the :doc:`/modtools/creation/requirements`

Configuring metadata
--------------------

All of the metadata for your map is stored in ``lebmod.json``

Customise the lebmod.json to the values of your map. See: :doc:`/modtools/uploading/jsonschema`

.. tip::
    If you do not have a proper text editor installed, try `Notepad++ <https://notepad-plus-plus.org/>`_ or `VSCode <https://code.visualstudio.com/>`_
