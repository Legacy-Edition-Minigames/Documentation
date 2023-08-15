I'm done, what now?
===========================
.. meta::
   :description lang=en: What to do after finishing your map.


Trimming the map
^^^^^^^^^^^^^^^^
To maintain compliance with the :doc:`/modtools/rules` battle maps must be under 25MB.
The easiset way of doing this is by trimming the unused content from the map files.
If you haven't already please make sure that the :doc:`/modtools/border` are setup correctly
To help with this process please carefully follow the instructions in this tutorial by PixeoGames:

.. image:: https://img.youtube.com/vi/mLcab7LR6VU/maxresdefault.jpg
    :alt: IMAGE ALT TEXT HERE
    :target: https://www.youtube.com/watch?v=mLcab7LR6VU



Submitting the map
^^^^^^^^^^^^^^^^^^
If you havent already please read :doc:`/modtools/github`. 
**Note: Submission method to be determinded by the LEM administration team.**


Maximum possible file saving
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. attention::
    This is **only for power users**. It is **not recommended** for regular maps.

To reiterate previous warning, the savings provided are very small, and it is **not recommended** for normal maps.
In order for the map to be loaded by the server the only sub-folders that are required are the:

* entities folder
* region folder

If your map needs to contain functioning villagers the ``poi`` folder is also required.
otherwise, all other folders and files in the world's folder can be discarded before compiling.
This will make the world unable to be loaded in singleplayer, so it is recommended to handle compilation 
and final file management on the github. Which will also improve the process when submitting.