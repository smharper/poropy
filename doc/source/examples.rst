.. _sec_examples:

Examples
========

.. highlight:: python
   :linenothreshold: 25

All examples are located in the ``poropy/examples`` and the 
reference output for all examples is in ``poropy/examples/output``.


.. _sec_smallcoreexamples:

Small Core Examples
-------------------

The first two examples use a small benchmark core to demonstrate 
basic capabilities of :mod:`poropy.coretools`.  The core is 
described in the theory documentation.  A helper script is 
included to build the reactor in ``poropy`` and is listed
here.

.. literalinclude:: ../../examples/small_core.py


.. _sec_smallcoremanual:

Example 1: Manual Scoping
"""""""""""""""""""""""""

:mod:`poropy.coretools` has several function to aid scoping
loading patterns by manually.  This shows a few.

.. literalinclude:: ../../examples/example01.py

Running it yields the following output:

.. literalinclude:: ../../examples/output/example01_ref
  


.. _sec_smallcoreoptimize:

Example 2: Optimizing a Core
""""""""""""""""""""""""""""

For this example, the optimization tools in :mod:`poropy.coretools.optimizer`
are demonstrated.  Many parameters are specific to 
`pypgapack <http://robertsj.github.com/pypgapack>`_.

.. literalinclude:: ../../examples/example02.py

Running it yields the following output:

.. literalinclude:: ../../examples/output/example02_ref



