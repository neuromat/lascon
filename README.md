# LASCON
This repository contains the source code of Latin American School on Computational Neuroscience (LASCON)'s static website.

This website is hosted at https://lascon.numec.prp.usp.br/.

## Release version notation

The notation used for release version is `vYEAR-MAJOR.MINOR.PATCH`. Examples of versions are:
* v2020-1.0.0
* v2025-0.5.0
* v1980-4.7.89

`YEAR` MUST correspond to the event's year. Since this is a simple static site (and thus does not declare an API),
the fields `MAJOR`, `MINOR` and `PATCH` does not have to follow the [Semantic Versioning 2.0.0](https://semver.org/) convention.
They are subjected to a more general interpretation: `MAJOR` and `MINOR` are used to declare major and minor changes and `PATCH` is for small fixes and patches. 


## Commit messages

Commit messages MUST follow the [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/).
Since this is a simple project, the only types we will probably use are:
* chore
* ci
* docs
* feat
* fix
* refactor
* revert
* style

Although the other types (like build, perf and test) are allowed. 
