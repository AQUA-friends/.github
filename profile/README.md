# AQUA friends

A community space for experimental, external, and independently maintained diagnostics built on top of the [AQUA core](https://github.com/DestinE-Climate-DT/AQUA) (Application for QUality Assessment).

AQUA Friends is designed to lower the barrier for collaboration around climate diagnostics while preserving the stability and maintainability of the official AQUA ecosystem. It provides a common home for diagnostics, utilities, workflows, and analysis tools that leverage AQUA core functionalities without requiring full integration into the official AQUA releases.

## Why AQUA friends?

AQUA has been developed within the context of the Destination Earth Programme Climate Adaptation Digital Twin (Climate DT).
The nature of long-term operational framework can make direct integration of external diagnostics difficult.
At the same time, AQUA is designed to allow independent usage of the core capabilities:

* data access through the Reader
* metadata fixing and homogenization
* regridding
* lazy and distributed processing with Xarray + Dask
* flexible CLI execution through `aqua analysis`

AQUA friends exists to bridge these two worlds.

## What belongs here?

If your diagnostic or tool:

* uses AQUA as data-access framework
* is not part of the operational framework of the ClimateDT
* does not follow coding standard or cycle releases of the ClimateDT or of the AQUA code
* is experimental or project-specific
* is not officially maintained by the AQUA team

then this organization may be the place where your repository can be developed.

## Phylosophy and relationship with AQUA

AQUA friends follows a lightweight and community-driven philosophy.
Each repository is:

* independently maintained
* free to choose its own dependencies and installation methods (e.g. which AQUA version to pin)
* encouraged (but not forced) to follow AQUA conventions

AQUA friends are then not forced to follow any AQUA or ClimateDT release cycle.
Repositories hosted here:

* are not officially supported by the AQUA core team
* may break with future AQUA versions
* may contain experimental or unstable code
* are developed under the responsibility of their maintainers

If a diagnostic or tool proves broadly useful and sufficiently mature, the AQUA core team may collaborate with its developers to:

* improve integration with AQUA
* align APIs or metadata conventions
* optimize performance
* eventually promote parts of the code into officially supported AQUA components if this is of the original developers interest
