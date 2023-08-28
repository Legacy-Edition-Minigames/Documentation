Toggling Custompack
===================
.. meta::
   :description lang=en: How to enable custompack

.. attention::
    This is **only for power users**. It is **not recommended** for regular users.

Enabling and Disabling Custompack
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Custompack can be enabled by using ``/trigger maptextures set -2``
Once you reload resources (either with ``/trigger reloadresources``, or reloging) the server will not load its custom assets.
Custompack can be disabled again by using ``/trigger maptextures set -2``

Developer Information
^^^^^^^^^^^^^^^^^^^^^^
Enabling a custompack normally requires a LEM server to be connected to the backend. This is because
the current implementation of custompack (since commit `68e042d <https://github.com/Legacy-Edition-Minigames/Minigames/commit/68e042d7035d465b5d797cafaa06daa5d76af84a>`_)
uses serverutils to save and load the value from the backend. If a server is disconnected, custompack cannot be enabled by following this guide.

If you are trying to enable custompack on a disconnected server, and you have admin, you can manually give yourself the tag using ``tag @s add custompack``

When a user enables custom pack ``lem.base:custompack`` 
is set to ``true``, When a player relogs the tag: ``custompack`` will tell the server to load the ``blank`` pack, which contains no assets.
Allowing the pack the user has equipped to override all server assets.
