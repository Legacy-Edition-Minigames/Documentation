Using ToolBox
=============
.. meta::
   :description lang=en: Using ToolBox to setup a server.

Launching ToolBox
^^^^^^^^^^^^^^^^^
As with the installation process, ToolBox can be launched by navigating to it's
containing folder and running ``java -jar Toolbox2.0.jar``

Setting up a server
^^^^^^^^^^^^^^^^^^^
After starting ToolBox, you can setup a new server.
Select an option from the ``New Servers`` list.

ToolBox will then prompt you to name this server, and configure the maximum
amount of RAM allocated to it.

.. tip::
   Most LEM servers need ~3GB of RAM to run.

After setting the server name and configuring RAM, ToolBox will begin installing
the required server dependencies.

.. notice::
   This can take a few minutes depending on the server option you selected initially.

You will then be prompted to accept the Minecraft EULA for your server.

After initial setup is complete, ToolBox will open the server options menu,
which you can use to start your server.

.. video:: /images/toolbox/installserver.mp4
   :muted:
   :autoplay:
   :loop:
   :width: 100%

Managing an installed server
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Once a server has been installed, when you next open ToolBox, it will appear
in the ``Installed Servers`` list.

Once you have selected the server, the server options menu will re-appear, this menu
is used to start, update, rename, delete, and export your server.

Launch Arguments
^^^^^^^^^^^^^^^^
Below is a list of launch arguments.

+------------------------------+-----------------------------------------------------+
| Argument                     | Function                                            |
+==============================+=====================================================+
| --server [ServerName]        | Sets target server name.                            |
+------------------------------+-----------------------------------------------------+
| --updateServer               | Updates targeted server if installed.               |
+------------------------------+-----------------------------------------------------+
| --launchServer               | Launches targeted server if installed.              |
+------------------------------+-----------------------------------------------------+
| --installServer              | Creates new server with target name.                |
+------------------------------+-----------------------------------------------------+
| --newServerRam [RAM GB]      | Sets new server ram to specified amount.            |
+------------------------------+-----------------------------------------------------+
| --newServerBranch [Branch]   | Sets new server to specified branch.                |
+------------------------------+-----------------------------------------------------+
| --newServerEULA [True/False] | Sets new server EULA agreement value.               |
+------------------------------+-----------------------------------------------------+
| --unattendedInstall          | Closes ToolBox after server installation completes. |
+------------------------------+-----------------------------------------------------+
| --autoRestart                | Restarts server if server is stopped.               |
+------------------------------+-----------------------------------------------------+
| --autoExit                   | Closes ToolBox if server is stopped.                |
+------------------------------+-----------------------------------------------------+
| --skipSplash                 | Skips ToolBox welcome splash on launch.             |
+------------------------------+-----------------------------------------------------+
