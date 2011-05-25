twisted-hl7
===========

Contents:

.. toctree::
   :maxdepth: 2

python-hl7 vs twisted-hl7
=========================

python-hl7 and twisted-hl7 are complementary python modules for handling HL7 data.

* twisted-hl7 provides a network-level HL7 implementation (MLLP)
* python-hl7 provides a HL7 parsing implementation

twisted-hl7 and python-hl7 can (and often are) used together.  But, the modular
approach allows a developer to substitute out either component.  For example,
a developer may not wish to use Twisted, instead he may elect to implement
the TCP server using :py:mod:`socket` or :py:mod:`asyncore`.  Likewise, a developer
may wish to use an alternate HL7 parsing routine, but still use twisted-hl7.

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
