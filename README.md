# EACLOCK-prototype
The code will be available soon!

PostgreSQL Database Management System
=====================================

This directory contains the source code distribution of the PostgreSQL
database management system.

PostgreSQL is an advanced object-relational database management system
that supports an extended subset of the SQL standard, including
transactions, foreign keys, subqueries, triggers, user-defined types
and functions.  This distribution also contains C language bindings.

PostgreSQL has many language interfaces, many of which are listed here:

	https://www.postgresql.org/download/

See the file INSTALL for instructions on how to build and install
PostgreSQL.  That file also lists supported operating systems and
hardware platforms and contains information regarding any other
software packages that are required to build or run the PostgreSQL
system.  Copyright and license information can be found in the
file COPYRIGHT.  A comprehensive documentation set is included in this
distribution; it can be read as described in the installation
instructions.

The latest version of this software may be obtained at
https://www.postgresql.org/download/.  For more information look at our
web site located at https://www.postgresql.org/.

After you compile and install successfully, please enter the following command on the client to select the page replacement algorithm you want:
\n
1, algorithm l: LRU
2, algorithm e: EACLOCK
3, algorithm s: Clock Sweep
4, algorithm h: hyperbolic
5, algorithm ed: EACLOCK-FDW
6, algorithm ew: EACLOCK-FWA
