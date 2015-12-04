python-opscripts
================

Python libraries to assist with writing Linux Ops scripts.


Python Version Target
=====================

This library currently targets Python version 2.6. It has been tested with the
following version of Python:

- 2.6.5
- 2.7.3, 2.7.6


API Versioning
==============

Each module is versioned so that they can undergo significant changes without
impacting the function and stability of the scripts that use them.

For example::

    from opscripts.config import v1 as ops_config
    from opscripts.logging import v1 as ops_logging
    from opscripts.utils import v1 as ops_utils


Dependencies
============

- `ConfigArgParse`_

.. _`ConfigArgParse`: https://github.com/bw2/ConfigArgParse


License
=======

- `<LICENSE>`_ (`MIT License`_)

.. _`MIT License`: http://www.opensource.org/licenses/MIT