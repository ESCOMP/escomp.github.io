# The Earth System Community Modeling Portal (ESCOMP)

This repository provides information about the [ESCOMP github
organization](https://github.com/ESCOMP).

## Management

The ESCOMP github organization is managed by the [University Corporation
for Atmospheric Research](https://www2.ucar.edu/).

## Policies for inclusion of a repository in this organization

The ESCOMP github organization is for large, community-oriented earth
system modeling projects of broad interest.

Projects stored here should meet all of the following criteria:

* They are related to earth system modeling in some way

* They are supported (e.g., if someone files an issue, it will be seen
  and addressed in some way)

* They are projects that have some involvement (typically strong
  involvement) from outside communities beyond the sponsoring
  organization (e.g., the university community or other agencies).
  Projects without outside collaboration should be stored elsewhere.

It is acceptable to store a fork in ESCOMP if this is the main
development fork for inclusion in a community-oriented modeling
project.

* For example, the primary repository for the MOM6 ocean model is stored
  in a GFDL github organization. However, NCAR maintains a fork of MOM6
  for use in CESM. It is acceptable to store NCAR's fork of MOM6 in
  ESCOMP so that it can appear alongside other CESM components, and
  because NCAR's MOM6 fork is still of broad interest to the community
  even though it isn't the primary fork.

* On the other hand, it is not acceptable to store a fork in ESCOMP if
  this fork is only used internally at NCAR and is not part of a broader
  community modeling project.

## Repository naming conventions

For repositories with an acronym as part or all of their name, we
generally prefer the use of uppercase acronyms. For example, we have
repositories named `CESM` and `CISM-wrapper`. An exception is
repositories that are used *solely* for hosting GitHub pages (i.e.,
websites appearing under escomp.github.io/): These can use lowercase
acronyms in order to have fully lowercase URLs. For example, we have a
repository named `ctsm-docs`. Repositories that are used for both code
and GitHub pages follow the uppercase convention (e.g., `CESM`); we can
put redirects in place so that links to the lowercase version redirect
to the uppercase version (e.g., `escomp.github.io/cesm` redirects to
`escomp.github.io/CESM`).

We have no standardization concerning the use of hyphens, underscores or
PascalCase to delineate separate words in a repository's name.
