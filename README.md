mkdeb recipes
=============

Recipes for the Debian packaging helper.

The source code is licensed under the terms of the [Apache License 2.0][license].

How to build a package?
-----------------------

To initialize or update your local copy of the recipes, run:

    mkdeb update

Then, to build a package, run:

    mkdeb build foo:amd64=1.2.3

Where `foo` is the package name, `amd64` the desired architecture and `1.2.3` the version number of upstream release.


[license]:      https://www.apache.org/licenses/LICENSE-2.0
