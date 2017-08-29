Modulefiles for use and testing of E. Davis's Python packages
installed in the PCI project directory of GA's Iris computational cluster.

Details regarding Iris can be found
[here](https://diii-d.gat.com/diii-d/Iris), while
particulars of modules and modulefiles can be found
[here](https://diii-d.gat.com/diii-d/Iris#Environment_modules).

Use:
----
Currently, this repository contains modulefiles for
five of E. Davis's github repositories:

* [random_data](https://github.com/emd/random_data),
* [filters](https://github.com/emd/filters),
* [mitpci](https://github.com/emd/mitpci),
* [bci](https://github.com/emd/bci), and
* [magnetics](https://github.com/emd/magnetics).

In addition to E. Davis's github repositories,
there are also modulefiles for the following:

* [a class for general data retrieval at DIII-D](
   https://diii-d.gat.com/diii-d/Gadata_py),
* [a color-blind proof set of distinct colors](
   https://personal.sron.nl/~pault/), and
* [least-squares fitting a set of points to an ellipse](
   https://github.com/ndvanforeest/fit_ellipse).

The modulefiles are named after their corresponding packages, and
they should require *no* modification for your own use on Iris.
The modules can be loaded, unloaded, etc.,
as is discussed in the above-linked Iris documentation.
For example, to load the `mitpci` module, type

    $ module load /fusion/projects/diagnostics/pci/code/python/modulefiles_pci/mitpci

That's it! The `mitpci` module can then be loaded and used in Python.
Information about the module and its automated testing can be obtained via

    $ module help /fusion/projects/diagnostics/pci/code/python/modulefiles_pci/mitpci

For frequent use of any of the above modules, it may be useful
to create aliases and/or load the modules in your login script.
