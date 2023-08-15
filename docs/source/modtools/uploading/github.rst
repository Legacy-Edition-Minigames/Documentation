Github Guide
===========================
.. meta::
   :description lang=en: What is Github, How do I use it?


What is Github?
^^^^^^^^^^^^^^^
Github is a popular place to host and store files that use
git version control. Which is a fancy way of saying, external file host with backups.
We use github as it provides easy uploading, and an understandable GUI for people to use.

How do I upload my map to github?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Create a github account `here <https://github.com/signup>`_
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
