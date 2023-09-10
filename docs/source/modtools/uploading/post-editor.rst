I'm done, what now?
===========================
.. meta::
   :description lang=en: What to do after finishing your map.


Trimming the map
^^^^^^^^^^^^^^^^
To maintain compliance with the :doc:`/modtools/creation/rules` battle maps must be under 25 MB.
The easiest way of doing this is by trimming the unused content from the map files.
If you haven't already please make sure that the :doc:`/modtools/creation/border` are set up correctly
To help with this process please carefully follow the instructions in this tutorial by PixeoGames:
`https://youtu.be/mLcab7LR6VU <https://youtu.be/mLcab7LR6VU>`_

.. image:: https://img.youtube.com/vi/mLcab7LR6VU/maxresdefault.jpg
    :alt: YouTube Video Tutorial
    :target: https://www.youtube.com/watch?v=mLcab7LR6VU



Submitting the map
^^^^^^^^^^^^^^^^^^
If you haven't already please read :doc:`/modtools/uploading/github`. 
**Note: Submission method to be determined by the LEM administration team.**


.. important::
    The following references features that are not currently available to the public.

1. Go to your Mod's Repository

    * Press the ``<> Code`` button.

    .. image:: /images/modtools/post-editor/code.png

    * Copy the link provided in the ``Local/HTTPS`` section.

    .. image:: /images/modtools/post-editor/copy.png

    * Save this link for later.


2. Go to `The Modtools Database <https://github.com/Legacy-Edition-Minigames/ModTools-Database/fork>`_

    * **DO NOT** change the name
    * Press ``Fork``

3. Download and install `git <https://git-scm.com/download/>`_ to your machine 

4. Once Git is installed, open your system's terminal.

    * Type in ``git clone https://github.com/Legacy-Edition-Minigames/ModTools-Database.git`` and press return/enter.
    * Type in ``cd Modtools-Database/Verified`` and press return/enter.
    * Type in ``git init`` and press return/enter.
    * Type in ``git submodule add``, paste in the link we copied in step 1. Your command should look something like this ``git submodule add https://github.com/username/mod.git`` Press Return/Enter.
    * Type in ``git commit -m "Added Mod"`` replacing ``Mod`` with your mod's name, then press return/enter.
    * Type in ``git branch -M main`` and press return/enter.
    * Type in ``git remote add origin git@github.com:username/Modtools-Database.git`` replacing ``username`` with your GitHub username. Then press return/enter.
    * Type in ``git push -u origin main`` and press return/enter.
    * You may need to sign in with GitHub in order to complete the commit.

5. Create a pull request.

    * Go to `The Pull Request Creator <https://github.com/Legacy-Edition-Minigames/ModTools-Database/compare>`_
    * Press ``compare across forks``.
    * Select your username from the dropdown
    * Create the Pull request

6. Wait

    * A moderator will review your pull request and request changes if needed.


Maximum possible file saving
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. attention::
    This is **only for power users**. It is **not recommended** for regular maps.

In order for the map to be loaded by the server the only sub-folders that are required are the ``entities`` folder and the
``region`` folder. If your map needs to contain functioning villagers the ``poi`` folder is also required.
Otherwise, all other sub-folders and files in the world's folder can be discarded before compiling.
This will make the world unable to be loaded in single-player, so it is recommended to handle compilation 
and final file management on GitHub.

To reiterate previous warning, the savings provided are very small, and it is **not recommended** for normal maps.