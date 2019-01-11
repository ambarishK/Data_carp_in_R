In order to use this Docker container to teach the Data Carpentry in R lessons (specifically the R & Databases lesson) I needed to add sqlite3
- Mark F. 2019

rocker/ropensci
==================

[![CircleCI](https://circleci.com/gh/rocker-org/ropensci.svg?style=svg)](https://circleci.com/gh/rocker-org/ropensci)

See the [rocker-org Wiki](https://github.com/rocker-org/rocker/wiki/) for details on use and development of this Docker image.

- `rocker/ropensci` image provides all rOpenSci packages currently on CRAN
- `rocker/ropensci:dev` image provides the Github versions of all rOpenSci packages listed on [ropensci.org](http://ropensci.org/packages)

Images are build on `rocker/hadleyverse` and updated regularly by automatic builds. (Latest build times visible on [docker hub](https://registry.hub.docker.com/u/rocker/ropensci/).  Images include RStudio-Server, see the wiki for use guidelines.
