# Testing submodules

Adding submodules from Github or [ETSI Forge](https://forge.etsi.org).

This repository contains submodules to the the GS MEC 011 OpenAPI repository in 2 different
ways:

* `forge-mec-011` is a submodule to the original repository at ETSI Forge,
* `github-mec-011` is a submodule to the repository mirrored on Github.

While both submodules are correctly handed, the submodule to the Github repository is displayed
with a clickable link, the submodule to the Forge is not.

Cloning the repository with `--recursive` strategy works correctly for both.
