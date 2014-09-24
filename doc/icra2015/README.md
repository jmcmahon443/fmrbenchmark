This directory contains LaTeX sources for the document that describes the
ICRA 2015 challenge.

Building
--------
There is a Makefile.  Besides providing for the usual `make` command, it also
defines the following commands.  Output is placed in `build/`

* `make date` : build, including in the file name "DRAFT" and the current
  timestamp (UTC)

* `clean` : delete everything under `build/`.


Dependencies
------------

* `images/network.xml` : <https://www.draw.io>
* `images/network.png` : generated from `images/network.xml`