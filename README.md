The [fmrbenchmark repository](https://github.com/fmrchallenge/fmrbenchmark) is
part of a project to develop benchmark problems for research in so-called formal
methods for robotics.  This effort is stimulated by competitions, and the main
website is https://fmrchallenge.org

Topical README files are provided in some directories.  For example,
`domains/dubins_traffic/README.md`.  In the documentation, `$FMRBENCHMARK`
represents an absolute path to your copy of the fmrbenchmark repository.


Summary of organization
-----------------------

* `doc/` : Documentation sources, including benchmark APIs, the User's Guide,
  and competition rules.

* `domains/` : Problem domains, e.g., `domains/integrator_chains/` contains code
  for the scaling chains of integrators setting.

* `tools/fmrb-pkg/` : Python package providing code for both common and
  domain-specific needs.

* `examples/` : contains example controllers and other demonstrations. An
  introduction to the examples is given below.

* `remote/` : scripts, configurations, etc. for running some or all of the
  benchmarks and supporting infrastructure remotely.


Documentation
-------------

The directory `doc/` contains sources for several components of documentation.

* `doc/norm/` : Normative problem domain descriptions and competition rules.
  Building requires [LaTeX](http://www.latex-project.org). Releases are
  available at https://fmrchallenge.org/norm

* `doc/api/` : API manual. Building requires [Doxygen](http://www.doxygen.org).
  Releases are available at http://api.fmrchallenge.org

* `doc/usersguide/` : User's Guide. Building requires [Sphinx](http://sphinx-doc.org).
  Releases are available at http://docs.fmrchallenge.org

If the appropriate tools are installed, as noted above, then go to the desired
directory and run `make`.


Examples
--------

There is a ROS meta-package for each problem domain that has name of the form
`DOMDIR_examples`, where the "DOMDIR" is the name of the directory under
`domains/` dedicated to that problem domain (benchmark).


License
-------

This is free software released under the terms of [the BSD 3-Clause License]
(http://opensource.org/licenses/BSD-3-Clause).  There is no warranty; not even
for merchantability or fitness for a particular purpose.  Consult LICENSE for
copying conditions.


Contributing
------------

There are many ways to contribute. Below is a summary. There is also a more
[detailed page](http://docs.fmrchallenge.org/en/latest/contributing.html) in
[the User's Guide](http://docs.fmrchallenge.org). All participation should
follow our [code of conduct](CODE_OF_CONDUCT.md).

* Join our mailing list, [fmrbenchmark-users@googlegroups.com](https://groups.google.com/forum/#!forum/fmrbenchmark-users)

* Find unassigned tasks or recommend solution methods in the
  [issue tracker](https://github.com/fmrchallenge/fmrbenchmark/issues).

Outside contributions should be submitted according to the fork-and-pull-request
workflow to facilitate a public record of review and discussion.  When doing so
is not appropriate or not easily possible, other media are welcome, e.g.,
sending patches via email.

All contributions must be under the standard "BSD 3-clause license" or a
comparable open-source license.
