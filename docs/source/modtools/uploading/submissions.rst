Submission handling
===================
.. meta::
   :description lang=en: Learn how to accept and update modtools submissions

This guide is for adding and updating mods to the ModTools Database repository on GitHub.

.. important::
   This should only be used **AFTER THE SUBMISSION HAS BEEN DEEMED AS ACCEPTED**.

   A mod should not be added to the ModTools Database until it has passed the moderation process.


Requirements
^^^^^^^^^^^^
#. Download and install `Git <https://git-scm.com/download/>`_ to your machine
#. Download the ModTools-Database and enter it

   * Open your system's terminal
   * Enter the directory you want to download the repository to
   * Download the files: ``git clone --recurse-submodules https://github.com/Legacy-Edition-Minigames/ModTools-Database.git``
   
   .. danger::
      This will download **ALL** the mods inside the ModTools Database, make sure you have the storage space for this.

   * Enter the new folder: ``cd ModTools-Database``


Add a new submission
^^^^^^^^^^^^^^^^^^^^
.. note::
   You are expected to have a terminal window open inside the ``ModTools-Database`` folder before continuing.

#. Make sure the repository is up to date: ``git checkout main``
#. Add the repository

   * Enter the correct category: ``cd Featured`` or ``cd Verified``
   * Add the repository as a submodule: ``git submodule add https://github.com/Username/repository-name``
   * Enter the submodule: ``cd repository-name``

#. Set it to the correct version

   * Check the releases page of the repository, and find the latest stable version of the mod

   .. image:: /images/modtools/submissions/findversion.png
   
   * Copy that version's hash
   
   .. image:: /images/modtools/submissions/copyhash.png
   
   * Set the submodule to the hash you just copied

     * ``git fetch``
     * ``git checkout <hash>``

#. Upload the changes

   * Go back up to the Verified or Featured folder: ``cd ..``
   * Add the updated submodule to the commit: ``git add repository-name``
   * Commit the changes: ``git commit -m "Added <map name> <version name>"``
   * Upload the changes: ``git push``


Update an existing submission
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. note::
   You are expected to have a terminal window open inside the ``ModTools-Database`` folder before continuing.

#. Make sure the repository is up to date: ``git checkout main``
#. Enter the submodule: ``cd repository-name``
#. Set it to the correct version

   * Check the releases page of the repository, and find the latest stable version of the mod

   .. image:: /images/modtools/submissions/findversion.png
   
   * Copy that version's hash
   
   .. image:: /images/modtools/submissions/copyhash.png
   
   * Set the submodule to the hash you just copied

     * ``git fetch``
     * ``git checkout <hash>``

#. Upload the changes

   * Go back up to the Verified or Featured folder: ``cd ..``
   * Add the updated submodule to the commit: ``git add repository-name``
   * Commit the changes: ``git commit -m "Updated <map name> to <version name>"``
   * Upload the changes: ``git push``
