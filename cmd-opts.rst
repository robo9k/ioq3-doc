====================
Command line options
====================

.. option:: -v, --version

    If this is the only option passed to ioquake3 it will print its
    version, including whether it's a dedicated server or client binary
    and the build date.

    Example::

        ioq3 1.36_GIT_7ae49cc-2013-11-02 client (Nov  3 2013)


.. option:: +set <cvar> <value>

    Allows to set a cvar, which will override its value from the default
    config files.
    This is also the only way to set cvars with the ``CVAR_INIT`` flag
    as a user.
