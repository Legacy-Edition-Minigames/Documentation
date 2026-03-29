Submitting your map
===================
.. meta::
   :description lang=en: How to submit your map to the server

.. note::
    This guide assumes you've done everything in :doc:`/modtools/uploading/post-editor`, make sure you read it before continuing.


Submitting a new map
^^^^^^^^^^^^^^^^^^^^
1. Create a new release

   Before submitting your map, you need to create a release to indicate what version of your map should be considered ready for use

   * Open your map on GitHub
   * Click on ``Releases`` on the right and select ``Create a new release``

    .. image:: /images/modtools/submitting/releases.png

    .. image:: /images/modtools/submitting/create.png


   * Click ``Select tag`` and create a new tag

    .. image:: /images/modtools/submitting/createtag.png

    .. image:: /images/modtools/submitting/nametag.png

    .. important::
        You should keep the names of your releases, tags, and version ID (from lebmod.json) consistent with each other.
    
    .. tip::
        If you have pushed commits after you pushed the version you consider ready and don't want the new commits to be a part of the release, select ``Target: main`` next to the version tag and ``Recent Commits`` to find the version you'd like to use 

   * If everything looks right, go ahead and click ``Publish release``

    .. image:: /images/modtools/submitting/publish.png


2. Go to `The Modtools Database submission form <https://github.com/Legacy-Edition-Minigames/ModTools-Database/issues/new/choose>`_

3. Click ``Submit a mod``.

    .. image:: /images/modtools/submitting/createissue.png
    
4. Fill out the form with information about your mod.

    .. image:: /images/modtools/submitting/fillform.png

5. Wait for a moderator to review your map, they will request changes if needed.

.. _submitting-update:

Submitting an update to your map
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
1. Create a new release

   Before submitting your update, you need to create a release to indicate what version of your map should be considered ready for use

   * Open your map on GitHub
   * Click on ``Releases`` on the right and select ``Draft a new release``

    .. image:: /images/modtools/submitting/releases.png

    .. image:: /images/modtools/submitting/draft.png


   * Click ``Select tag`` and create a new tag

    .. image:: /images/modtools/submitting/createtag.png

    .. image:: /images/modtools/submitting/nametag2.png

    .. note::
        You should keep in mind if your update is a major or minor update when picking a version number, for example:

        If the update is minor, you should only increase the second (or third) digit, such as ``1.0`` to ``1.1``

        If the update is major, you should increase the first digit and set the rest to 0, such as ``1.1`` to ``2.0``

    .. important::
        You should keep the names of your releases, tags, and version ID (from lebmod.json) consistent with each other.
    
    .. tip::
        If you have pushed commits after you pushed the version you consider ready and don't want the new commits to be a part of the release, select ``Target: main`` next to the version tag and ``Recent Commits`` to find the version you'd like to use 

   * Write a list of what this update changes in the description

   * If everything looks right, go ahead and click ``Publish release``

    .. image:: /images/modtools/submitting/publish2.png

2. Go to `The Modtools Database <https://github.com/Legacy-Edition-Minigames/ModTools-Database/issues>`_

3. Find your map that you want to submit an update to

    .. image:: /images/modtools/submitting/search.png

4. Leave a comment mentioning that you have made an update with a changelog of the changes you have made.

5. Wait for a moderator to review your map, they will request changes if needed.
