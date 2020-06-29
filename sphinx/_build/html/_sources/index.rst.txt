.. Grin documentation master file, created by
   sphinx-quickstart on Mon Jun 29 16:58:34 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Grin's documentation!
================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Introduction to Mimblewimble and Grin
-------------------------------------

Mimblewimble is a blockchain format and protocol that provides extremely
good scalability, privacy and fungibility by relying on strong
cryptographic primitives. It addresses gaps existing in almost all
current blockchain implementations.

Grin is an open source software project that implements a Mimblewimble
blockchain and fills the gaps required for a full blockchain and
cryptocurrency deployment.

Here’s an overview:

-  Clean and minimal implementation, and aiming to stay as such.
-  Follows the MimbleWimble protocol, which provides great anonymity and
   scaling characteristics.
-  Cuckoo Cycle proof of work.
-  Relatively fast block time: one minute.
-  Fixed block reward over time with a decreasing dilution.
-  Transaction fees are based on the number of Outputs created/destroyed
   and total transaction size.
-  Smooth curve for difficulty adjustments.

Goal and Characteristics
------------------------

Privacy by Default
~~~~~~~~~~~~~~~~~~

This enables complete fungibility without precluding the ability to
selectively disclose information as needed. Scales mostly with the
number of users and minimally with the number of transactions (<100 byte
kernel), resulting in a large space saving compared to other
blockchains.

Strong and proven cryptography
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Mimblewimble only relies on Elliptic Caurve Cryptography which has been
tried and tested for decades.

Design simplicity
~~~~~~~~~~~~~~~~~

Easy to audit and maintain over time

Community driven
~~~~~~~~~~~~~~~~

Community driven, encouraging mining decentralization. No ICO, Founder
reward, pre-mine or aidrop.

Contents
========

:ref:`Keyword Index <genindex>`, :ref:`Search Page <search>`

.. toctree::
   :maxdepth: 2
   :caption: Integration

   integration/index.rst

.. toctree::
   :maxdepth: 2
   :caption: Technical Details

   technical/table-of-contents.rst
   technical/introduction-to-mimblewimble.rst


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
