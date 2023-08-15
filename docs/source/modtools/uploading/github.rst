GitHub Guide
===========================
.. meta::
   :description lang=en: What is GitHub, How do I use it?


What is GitHub?
^^^^^^^^^^^^^^^
GitHub is a popular place to host and store files that use
git version control. Which is a fancy way of saying, external file host with backups.
We use GitHub as it provides easy uploading, and an understandable GUI for people to use.

How do I upload my map to GitHub?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Create a GitHub account `here <https://github.com/signup>`_

2. Once signed in, go to `this site <https://github.com/new?template_name=Example-LEM-Mod&template_owner=Legacy-Edition-Minigames>`_

    * For `Repository name` put in your map name.
    * Make sure it is set to public
    * Press Create Repository

3. Delete the example files

    * Go into the ``src`` folder
    * Go into the ``world`` folder
    * Go into the ``large`` folder
    * Press on more options

    .. image:: /images/editor/github/moreoptions.png

    * Delete the directory

4. Upload your files 

    * Go back to the ``world`` folder
    * Click add files
    * Click Upload files
    * Upload your custom map's folder, (make sure the name matches the map size you are using)
    * Press commit changes

5. Customise the lebmod.json

    * Go back to the ``src`` folder
    * Click on ``lebmod.json``
    * Click on the pen icon
    * Customise the lebmod.json to the values of your map. See: :doc:`/modtools/uploading/editorjsonschema`



Map Submission
^^^^^^^^^^^^^^

.. important::
    The following references features that are not currently available to the public.

1. Go to your Mod's Repository

    * Press the ``<> Code`` button.

    .. image:: /images/editor/github/code.png

    * Copy the link provided in the ``Local/HTTPS`` section.

    .. image:: /images/editor/github/copy.png

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
