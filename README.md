About splore
============

Home: https://github.com/SimonBoothroyd/splore

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/simonboothroyd/splore-feedstock/blob/master/LICENSE.txt)

Summary: A GUI for exploring sets of molecules

Development: https://github.com/SimonBoothroyd/splore

Documentation: https://github.com/SimonBoothroyd/splore

The splore framework aims to offer a simple graphical interface for scrolling through
and exploring data sets of molecules.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/simonboothroyd/feedstock-builds/_build/latest?definitionId=11&branchName=master">
        <img src="https://dev.azure.com/simonboothroyd/feedstock-builds/_apis/build/status/splore-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-splore-green.svg)](https://anaconda.org/SimonBoothroyd/splore) | [![Conda Downloads](https://img.shields.io/conda/dn/SimonBoothroyd/splore.svg)](https://anaconda.org/SimonBoothroyd/splore) | [![Conda Version](https://img.shields.io/conda/vn/SimonBoothroyd/splore.svg)](https://anaconda.org/SimonBoothroyd/splore) | [![Conda Platforms](https://img.shields.io/conda/pn/SimonBoothroyd/splore.svg)](https://anaconda.org/SimonBoothroyd/splore) |

Installing splore
=================

Installing `splore` from the `SimonBoothroyd` channel can be achieved by adding `SimonBoothroyd` to your channels with:

```
conda config --add channels SimonBoothroyd
conda config --set channel_priority strict
```

Once the `SimonBoothroyd` channel has been enabled, `splore` can be installed with:

```
conda install splore
```

It is possible to list all of the versions of `splore` available on your platform with:

```
conda search splore --channel SimonBoothroyd
```




Updating splore-feedstock
=========================

If you would like to improve the splore recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`SimonBoothroyd` channel, whereupon the built conda packages will be available for
everybody to install and use from the `SimonBoothroyd` channel.
Note that all branches in the simonboothroyd/splore-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@simonboothroyd](https://github.com/simonboothroyd/)

