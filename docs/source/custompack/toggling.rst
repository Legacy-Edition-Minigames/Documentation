Toggling Custompack
===================
.. meta::
   :description lang=en: How to enable custompack

.. danger::
    This is **only for power users**. It is **not recommended** for regular users.

    Using this could cause usability issues, proceed with caution.

Enabling and Disabling Custompack
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Custompack can be enabled by using ``/trigger maptextures set -2``
Once you reload resources (either with ``/trigger reloadresources``, or reloging) the server will not load its custom assets.
Custompack can be disabled again by using ``/trigger maptextures set -2``

Developer Information
^^^^^^^^^^^^^^^^^^^^^^

When a user enables custom pack ``lem.base:custompack`` 
is set to ``true``, When a player relogs the tag: ``custompack`` will tell the server to load the ``blank`` pack, which contains no assets.
Allowing the pack the user has equipped to override all server assets.
