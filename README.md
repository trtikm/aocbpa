Anonymous On-line Communication Between Program Analyses
========================================================

The project provides a light-weight client-server model of communication
between program analyses. Clients are individual analyses and
the server mediates their communication. A client cannot see properties
of any other and the communication is anonymous. There is no central
algorithm standing above clients which would tell them when to
communicate what information. Clients communicate with others spontaneously,
according to their actual personal needs. The model is based
on our observation that a piece of information provided to an analysis
at a right place may (substantially) improve its result.
