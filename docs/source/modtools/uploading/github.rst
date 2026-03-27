GitHub Guide
============
.. meta::
   :description lang=en: What is GitHub, How do I use it?


What is GitHub?
^^^^^^^^^^^^^^^
GitHub is a popular place to host and store files that use
git version control. Which is a fancy way of saying, external file host with backups.
We use GitHub as it provides an easy way for us to handle submissions and tracking updates


Requirements
^^^^^^^^^^^^
1. Create a GitHub account `here <https://github.com/signup>`_

2. If you are unfamiliar with git, install GitHub Desktop.

    `[Windows & MacOS] <https://desktop.github.com/download/>`_ `[Linux] <https://github.com/shiftkey/desktop#readme>`_


How do I upload my map to GitHub?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. warning::
    **WARNING WARNING WARNING!!!**
    
    Submissions are **NOT ENABLED YET!!!** We are still working on finalizing the process for submissions.

    Please wait for submissions to become available. Thank you.

1. Once you are signed in to GitHub, go to `this site <https://github.com/new?template_name=Example-LEM-Mod&template_owner=Legacy-Edition-Minigames>`_

    * For `Repository name` put in your map name.
    * Make sure it is set to public
    * Press Create Repository

2. Open GitHub Desktop, and sign into it

    * Select ``File`` at the top left, and click ``Clone repository``

    .. image:: /images/modtools/github/clone.png

    * Click on your map's repository name, and then ``Clone`` in the bottom right

    .. image:: /images/modtools/github/clonemenu.png

3. Delete the example files

    * Select ``Repository`` at the top and click ``Show in your File Manager``

    .. image:: /images/modtools/github/openfolder.png

    * Go into the ``src`` folder
    * Go into the ``world`` folder
    * Delete the ``largeplus`` folder

    * Delete the directory

4. Exit the world in Minecraft, and locate your world's folder

   * Before closing the world, go to the center of the map and press F3 and make note note of your coordinates and save them for later.
   * To get to the folder, go to ``Singleplayer`` -> ``Edit`` -> ``Open world folder``

    .. image:: /images/modtools/install-editor/edit-button.png

    .. image:: /images/modtools/install-editor/openworldfolder-button.png

5. Add your custom map's files

    .. note::
        There are 4 possible map types, ``small``, ``large``, ``largeplus``, and ``remastered``

        More information can be found on the :doc:`/modtools/creation/requirements`

    * Create a folder and name it the map type your world is
    * Enter the new folder
    * Copy your custom map's world data to the new folder

    .. video:: /images/modtools/github/copyworld.mp4
        :muted:
        :autoplay:
        :loop:
        :width: 100%

5. Customise the lebmod.json

    * Go back to the ``src`` folder
    * Open ``lebmod.json`` in a text editor
    * Customise the lebmod.json to the values of your map. See: :doc:`/modtools/uploading/jsonschema`

    .. tip::
        If you do not have a proper text editor installed, try `Notepad++ <https://notepad-plus-plus.org/>`_ or `VSCode <https://code.visualstudio.com/>`_

5. Upload your changes

    * Go to Github Desktop and make sure all the files are selected by clicking on the top tickbox in the top left and making sure it is checked

    .. image:: /images/modtools/github/selectfiles.png

    * Go down to the summary box at the bottom and make a name for your changes, something like ``Upload map data`` would be fine
    * Click on the ``Commit to main`` button

    .. image:: /images/modtools/github/commit.png

    * Click the ``Push origin`` button

    .. image:: /images/modtools/github/pushorigin.png

Your map repository is now on github! To continue with the map submission process see :doc:`/modtools/uploading/submitting`


How do I upload an update of my map?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
1. Open your map's new world folder

   * To get to the folder, go to ``Singleplayer`` -> ``Edit`` -> ``Open world folder``

    .. image:: /images/modtools/install-editor/edit-button.png

    .. image:: /images/modtools/install-editor/openworldfolder-button.png


2. Open your map's repository folder

    * Open GitHub Desktop
    * Select ``Repository`` at the top and click ``Show in your File Manager``

    .. image:: /images/modtools/github/openfolder.png

3. Replace the world data in your map's repository

   * Navigate to ``src``
   * Enter the folder for the map type you are updating

    .. note::
        There are 4 possible map types, ``small``, ``large``, ``largeplus``, and ``remastered``

        More information can be found on the :doc:`/modtools/creation/requirements`

   * Delete the old world data and replace it with your new version
   
    .. caution::
        Make sure that you delete the **OLD** world data from your map's repository, **NOT** the new data you are getting from Minecraft
    
    .. video:: /images/modtools/github/replaceworld.mp4
        :muted:
        :autoplay:
        :loop:
        :width: 100%

4. Update your lebmod.json

   After making an update, you should review lebmod.json and see if it needs any changes

    * Go back to the ``src`` folder
    * Open ``lebmod.json`` in a text editor
    * Update the ``version`` option to reflect your map's new version number
    * Check to make sure if anything else needs to be updated. For example if you added a new map type, you will need to enable it and enter its coordinates

    If you are unsure what these options do, see: :doc:`/modtools/uploading/jsonschema`

    .. tip::
        If you do not have a proper text editor installed, try `Notepad++ <https://notepad-plus-plus.org/>`_ or `VSCode <https://code.visualstudio.com/>`_


4. Upload your changes

    * Go to Github Desktop and make sure all the files are selected by clicking on the top tickbox in the top left and making sure it is checked

    .. image:: /images/modtools/github/selectfiles.png

    * Go down to the summary box at the bottom and make a name for your changes, either describe the update or just use a version number
    * Click on the ``Commit to main`` button

    .. image:: /images/modtools/github/commit2.png

    * Click the ``Push origin`` button

    .. image:: /images/modtools/github/pushorigin.png

Your map repository is now on github! To continue with the map submission process see :ref:`submitting-update`
