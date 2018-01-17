discodb
=======

This is an INCOMPLETE, UNFINISHED HACK at porting this project to
Python 3-only. As of yet it does not pass tests, and the interface is
not correct. Please do not use! Please see

https://github.com/discoproject/discodb/issues/12#issuecomment-358389533

for a discussion of where discodb's python interface should go. See

https://github.com/goller/discodb

for a different attempt at the same thing.

----------------------------------------------------------------------

An efficient, immutable, persistent mapping object.

See documentation at http://discodb.readthedocs.org

Use the Makefile to build, e.g.::

    make
    make erlang
    make python
    make python CMD=install
    make utils
