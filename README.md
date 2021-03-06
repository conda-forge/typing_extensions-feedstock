About typing_extensions
=======================

Home: https://github.com/python/typing/tree/master/typing_extensions

Package license: PSF-2.0

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/typing_extensions-feedstock/blob/master/LICENSE.txt)

Summary: Backported and Experimental Type Hints for Python

Development: https://github.com/python/typing

Documentation: https://github.com/python/typing

The typing module was added to the standard library in Python 3.5 on a
provisional basis and will no longer be provisional in Python 3.7. However,
this means users of Python 3.5 - 3.6 who are unable to upgrade will not be
able to take advantage of new types added to the typing module, such as
typing.Text or typing.Coroutine.

The typing_extensions module contains both backports of these changes
as well as experimental types that will eventually be added to the typing
module, such as Protocol.

Users of other Python versions should continue to install and use the
typing module from PyPi instead of using this one unless specifically
writing code that must be compatible with multiple Python versions or
requires experimental types.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5848&branchName=master">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/typing_extensions-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-typing--extensions-green.svg)](https://anaconda.org/conda-forge/typing-extensions) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/typing-extensions.svg)](https://anaconda.org/conda-forge/typing-extensions) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/typing-extensions.svg)](https://anaconda.org/conda-forge/typing-extensions) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/typing-extensions.svg)](https://anaconda.org/conda-forge/typing-extensions) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-typing_extensions-green.svg)](https://anaconda.org/conda-forge/typing_extensions) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/typing_extensions.svg)](https://anaconda.org/conda-forge/typing_extensions) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/typing_extensions.svg)](https://anaconda.org/conda-forge/typing_extensions) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/typing_extensions.svg)](https://anaconda.org/conda-forge/typing_extensions) |

Installing typing_extensions
============================

Installing `typing_extensions` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `typing-extensions, typing_extensions` can be installed with:

```
conda install typing-extensions typing_extensions
```

It is possible to list all of the versions of `typing-extensions` available on your platform with:

```
conda search typing-extensions --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating typing_extensions-feedstock
====================================

If you would like to improve the typing_extensions recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/typing_extensions-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@djsutherland](https://github.com/djsutherland/)
* [@synapticarbors](https://github.com/synapticarbors/)

