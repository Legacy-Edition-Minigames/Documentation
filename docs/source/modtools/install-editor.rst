Installing the Map Editor
=========================

To be able to add map data for ModTools (spawnpoints, borders, chests, etc) you must install the Editor DataPack first.

Before installing to a world, you must download the editor from `GitHub <https://github.com/Legacy-Edition-Minigames/ModTools/releases/latest>`_

.. important::
    Make sure you are on Minecraft ``1.20`` or ``1.20.1`` before proceeding.

Make sure to download the file named ``ModTools-Editor`` and not ``Source Code``

.. _installing-to-a-world:
Installing to a new world
-------------------------

In the create new world menu, select the ``More`` tab.

.. image:: /images/editor/install-editor/tab.png

Select the ``Data Packs`` button

.. image:: /images/editor/install-editor/datapack-button.png

Select the ``Open Pack Folder`` button and copy the ``ModTools-Editor.zip`` file to the opened folder.

.. image:: /images/editor/install-editor/openpackfolder-button.png

You should see the datapack in the ``Available`` side of the menu.

.. image:: /images/editor/install-editor/availablepacks.png

Click on the datapack's icon to enable it.

.. image:: /images/editor/install-editor/selectedpacks.png

From this point, you may configure your world's settings to your liking.

Installing to an existing world
-------------------------------

Go to your singleplayer menu, click once on the world you wish to install the editor to and click the ``Edit`` button at the bottom.

.. image:: /images/editor/install-editor/edit-button.png

Select the ``Open World Folder`` button.

.. image:: /images/editor/install-editor/openworldfolder-button.png

Inside of the folder you opened, open the ``datapacks`` folder.

Copy the ``ModTools-Editor.zip`` file to the opened folder.

Enter the world from the singleplayer menu.

Installing the resource pack
----------------------------

.. error::
    The editor resource pack is not complete, a tutorial will need to be made later.

.. _updating:
Updating the Editor
-------------------
.. attention::
    Updating to the new Modtools Editor is not yet supported, and will comprimise the world file if attempted.
    The built in updater for the Modtools Editor Datapack will be unable to update the map to the newest release
    if it is installed in this state. Proceed at your own risk.

If you are updating from the previous version of Modtools ``DP-0.1`` to the new Modtools Editor.
Replace the old datapack in the folder `Instructions here <modtools/install-editor#installing-to-a-world>`_
with the new Modtools Editor Datapack. Once you load back into the work the Editor will update all pre-existing
entities to the new versioning scheme, giving them the ``lem.mt.version`` value of ``1``.