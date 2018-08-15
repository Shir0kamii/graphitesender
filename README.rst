Graphitesender
##############

Graphitesender allow you to send metrics to any graphite server.

Installation
============

Graphitesender is available on pypi:

.. code-block:: bash

    pip install graphitesender

Usage
=====

Assuming your hostname is *bob* and your graphite instance is on
*example.com*:

.. code-block:: python

    from graphite import GraphiteClient

    client = GraphiteClient("example.com")
    client.send("foo", 42)

This will send the metric *systems.bob.foo* with the value *42* and the
current timestamp

Graphitesend
============

Graphitesender is a fork of graphitesend_. This fork is here because with the
author of graphitesend gone, there was no way to publish new versions.

A lot of things will change with this fork, but any breaking change will happen
six months after its notice. Most often in the form of a deprecation.

Since the fork, the following changes has been made:

* None that matter yet

Roadmap
=======

* Deprecate then remove the myriad of formatting arguments, replacing it with
  a better interface
* Rework module functions, that should be simple proxies
* Isolate sending implementation to make it interchangeable

.. _graphitesend: https://github.com/daniellawrence/graphitesend