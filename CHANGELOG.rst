Changelog
#########

0.11.2
======

* Drop Python 2.6 support
* Fix Python 2.7 compatibility

0.11.1
======

* Stop replacing '-' with '_'

0.11.0
======

* Allow to pass formatter to the client, and deprecate all arguments forwarded
  to the formatter
* Implement block metrics
* Add argparse as optional dependency.
* Define Client's default port as class attribute.
* Remove Client's proxies to formatter attributes.
* Reset test architecture with pytest. The tests doesn't cover much for now, but
  more will be added as the development goes on.

0.10.0 and before
=================

Please see the changelog of graphitesend_. Graphitesender is born from of fork
of its version 0.10.0.

.. _graphitesend: https://github.com/daniellawrence/graphitesend
