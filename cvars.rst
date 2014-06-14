=====
cvars
=====

vm_game
=======

:flags: ``CVAR_ARCHIVE``
:default: ``2``
:type: enum (``vmInterpret_t``)

Determines how the ``game`` module is loaded.

Possible values:

``0`` aka ``VMI_NATIVE``
    Try to load a native shared library, but fall back to QVM file if
    not found.

``1`` aka ``VMI_BYTECODE``
    Load a QVM file and interpret it.

    .. note::
        This is also the fallback for architectures that do not
        have a QVM compiler implementation.

``2`` aka ``VMI_COMPILED``
    Load a QVM file and compile it to native machine instructions.
