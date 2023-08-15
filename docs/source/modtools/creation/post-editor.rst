I'm done, what now?
===========================
.. meta::
   :description lang=en: What to do after finishing your map.


Trimming the map
^^^^^^^^^^^^^^^^
To maintain compliance with the :doc:`/modtools/creation/rules` battle maps must be under 25MB.
The easiest way of doing this is by trimming the unused content from the map files.
If you haven't already please make sure that the :doc:`/modtools/creation/border` are setup correctly
To help with this process please carefully follow the instructions in this tutorial by PixeoGames:
`https://youtu.be/mLcab7LR6VU <https://youtu.be/mLcab7LR6VU>`_

.. image:: https://img.youtube.com/vi/mLcab7LR6VU/maxresdefault.jpg
    :alt: Youtube Video Tutorial
    :target: https://www.youtube.com/watch?v=mLcab7LR6VU



Submitting the map
^^^^^^^^^^^^^^^^^^
If you haven't already please read :doc:`/modtools/uploading/github`. 
**Note: Submission method to be determined by the LEM administration team.**


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