Exporting/Importing Servers
===========================
.. meta::
   :description lang=en: Export and Import a configured server.

Packaged Servers
^^^^^^^^^^^^^^^^
In some cases, you might need to setup a server with a specific configuration
more than once, for example if you had a specific set of ModTools maps you wanted
on more than one server.

To make this process easier ToolBox supports Exporting and Importing your servers.
You can share these exported servers with friends, or they may be requested by developers
to help with support.

Exporting a Server
^^^^^^^^^^^^^^^^^^
With a server selected, you can select the ``Share Install`` option, this will package
your entire server into a ``.toolbox`` file, saved as ``[ToolBox Directory]/packaged/[Server Name].toolbox`` 

.. note::
   This can take a few minutes to complete.

.. video:: /images/toolbox/exportserver.mp4
   :muted:
   :autoplay:
   :loop:
   :width: 100%

Importing a Server
^^^^^^^^^^^^^^^^^^
If you have a packaged ``.toolbox`` file, you can place it into ToolBox's ``installs`` directory.
From there, you can open ToolBox and select the ``Import a packaged .toolbox server`` option.

From there you can discover the packaged servers in the ``installs`` directory, and ToolBox
will automatically import the server into your ``Installed Servers`` list.

The imported server will have the name ``[Server Name] (Imported)`` to help distinguish it from 
other installed servers.

.. video:: /images/toolbox/importserver.mp4
   :muted:
   :autoplay:
   :loop:
   :width: 100%

