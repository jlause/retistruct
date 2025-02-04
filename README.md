Retistruct v0.5.12_local 
==========

This is a fork of David C Sterratt's `retistruct v0.5.12`, customized to quickly export projected datapoints as CSV files when using the SAVE button in th GUI.

To install this version, it's helpful to have the R package `devtools` installed. Then, in R, call:

```
devtools::install_github("jlause/retistruct@v0.5.12_local", subdir="pkg/retistruct")
```


To fix a recent issue with the geometry package used by retistruct, make sure to install the most recent version of that staight from David Sterratt's github repo:
```
devtools::install_github("davidcsterratt/geometry", subdir="pkg")
```

To start, use

```
library(retistruct)
retistruct()
```

in R. During the first run, R will install some additional packages.


Changelog:

-Disabled KDE/Countour computation for speed

-Disabled .mat file saving for speed

-Added CSV file saving for spherical and cartesian coordinates (for each dataset)

---

From the original repo:

_computational reconstruction and transformation of flattened retinae_

Retistruct is an R package to morph a flat surface with cuts (a
dissected flat-mount retina) onto a curvilinear surface (the a
standard retinal shape). It can estimate the position of a point on
the intact adult retina to within 8? of arc (3.6% of nasotemporal
axis). The coordinates in reconstructed retinae can be transformed to
visuotopic coordinates.

For full details go to the home page: http://davidcsterratt.github.io/retistruct/
