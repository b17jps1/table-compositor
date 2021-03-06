Introduction
=============

The table-compositor library provides the API to render data stored in table-like data structures. Currently the library only supports rendering data available in a Panda's DataFrames. The DataFrame layout is used as the table layout(including single and multi hierarchical columns/indices) by the library. The table layout is rendered directly on to an xslx sheet or to a html page. Styling and layout attributes can be used to render colorful xlsx or html reports. The library also supports rendering of multiple data frames into a single xlsx sheet or html page (with horizontal/vertical layouts). The objective of the library is to be able to use the DataFrame as the API to configure the style and layout properties of the report.  Callback functions are provided to customize all styling properties. The nice thing about the callback functions are that the style properties are set on cells indexed with index/column values available in the original dataframe used during rendering.

Code: https://github.com/InvestmentSystems/table-compositor

Docs: http://table-compositor.readthedocs.io

Packages: https://pypi.python.org/pypi/table-compositor


Getting Started
----------------

The table-compositor library builds on the concept of Panda's DataFrame as API to render colorful reports. The various ways of providing styling attributes and choosing layouts are demonstrated with numerous examples in the documentation.  Please refer to the Bacis section of the documentation to get started with the HelloWorld example.


Installation
------------------

A standard setuptools installer is available via PyPI:

https://pypi.python.org/pypi/table-compositor


Or, install via pip3:

.. code-block:: none

    pip3 install table-compositor


Source code can be obtained here:

https://github.com/InvestmentSystems/table-compositor
