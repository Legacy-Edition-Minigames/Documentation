Compiling your map
==================
.. meta::
   :description lang=en: How to compile a map directory into a .lebmod file

.. attention::
    This step is **Not nessecary** if you are just planning to upload your map to the public server.

    This is intended for users that want to install their map on a ToolBox server.


Make sure you have finished :doc:`/modtools/creation/directory`

.. important::
    Make sure your map meets the :doc:`/modtools/creation/requirements`, or else you may encounter errors when trying to load your map in-game

What is the compiling process?
------------------------------

Compiling your map packages it up into a single file for the installer to read from.

Running the compiler
--------------------

.. note::
    `Python <https://www.python.org/downloads/>`_ must be installed before proceeding.

1. Go to the `ModTools repository <https://github.com/Legacy-Edition-Minigames/ModTools>`_ and download the source code


  * Click on the ``<> Code`` button
  * Click ``Download ZIP`` and save the file
  * Extract it and copy ``LEB-ModCompiler.py`` to your map's directory

2. Run ``LEB-ModCompiler.py`` 

   * The compiler will create a folder named ``output``
   * If everything has gone right, your map should be in that folder as a ``.lebmod`` file.

Installing to a ToolBox server
------------------------------

From here, if you want to install your mod to a ToolBox server, check the ToolBox documentation

.. error::
    The ToolBox documentation does not exist yet.
