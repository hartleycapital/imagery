# Satellite imagery (licensed SkyFi / Vantor deliveries)

Raw deliveries for the Nederland (TX) and Cushing (OK) tank-farm work, one folder
per order line as delivered. Large rasters (TIF, PNG) are stored with Git LFS.

The pipeline reads these through symlinks at their original `~/Downloads/SkyFi_*`
paths, so `nederland-map/data/deliveries.json` and the cushing-map scripts need no
changes. To restore on a new machine: clone, run `git lfs pull`, then recreate the
symlinks (or update the paths in deliveries.json).

Private and internal. Licensed imagery: not for redistribution.
