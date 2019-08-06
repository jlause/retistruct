Retistruct v0.5.12_local 
==========

This is a fork of `retistruct v0.5.12`, customized to quickly export projected datapoints as CSV files when using the SAVE button in th GUI.

To install this version, it's helpful to have the R package `devtools` installed. Then, in R, call:

```
devtools::install_github("jlause/retistruct@v0.5.12_local", subdir="pkg/retistruct")
```

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
