About cpplint
=============

Home: https://github.com/cpplint/cpplint

Package license: BSD-3-Clause

Feedstock license: BSD-3-Clause

Summary: A publicly maintained version of Google's static analysis tool for C/C++ code.

Cpplint is a command-line tool to check C/C++ files for style issues
following Google's C++ style guide. Cpplint is developed and maintained by
Google Inc. at google/styleguide, also see see the wikipedia entry.

While Google maintains cpplint, Google is not (very) responsive to issues
and pull requests, this fork aims to be (somewhat) more open to add fixes to
cpplint to enable fixes, when those fixes make cpplint usable in wider
contexts.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=175&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/cpplint-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-cpplint-green.svg)](https://anaconda.org/nsls2forge/cpplint) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/cpplint.svg)](https://anaconda.org/nsls2forge/cpplint) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/cpplint.svg)](https://anaconda.org/nsls2forge/cpplint) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/cpplint.svg)](https://anaconda.org/nsls2forge/cpplint) |

Installing cpplint
==================

Installing `cpplint` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `cpplint` can be installed with:

```
conda install cpplint
```

It is possible to list all of the versions of `cpplint` available on your platform with:

```
conda search cpplint --channel nsls2forge
```




Updating cpplint-feedstock
==========================

If you would like to improve the cpplint recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/cpplint-feedstock are
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


