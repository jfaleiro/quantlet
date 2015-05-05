QuantLET
========

QuantLET is an open source, event-driven framework for 
rapid development and deployment of real-time analytical 
models intended to be executing in large scale, 
in terms of data intensiveness or computing power 
(your spreadsheet can’t do that).

You can see a [few examples of the framework](https://quantlet.wordpress.com/box) outlining the use of signals in a moving average cross-over strategy or how to define and use 'infinite spreadsheets'.

This project has been moved to [GitLab](https://gitlab.com/jfaleiro/quantlet). 

The nature of a quantitative framework require a number of quite heavy auxiliary library and resources. You can pick and choose  a specific module based on what you intend to do with the framework.

quantlet-core
-------------

Core elements of the framework: streams, reactives, graphs and concurrency. This is the minimum you will need for basic use cases.

quantlet-analytics
------------------

Elements of numeric processing, data analysis, plotting and tabular transformations (filtering, aggregations, time series, data frames, etc)

quantlet-agents
---------------

Synchronous and assynchronous agents for discrete-event simulation. 

quantlet-bigdata
----------------

Support for usecases that must reply on very large data: infinite reactive graphs (infinite spreadsheets) and NOSQL repositories.

quantlet-scratchpad
-------------------

Support for interactive use and elaborate visualization resources



