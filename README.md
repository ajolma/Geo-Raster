Geo-Raster
==========

Perl extension for geospatial rasters

DESCRIPTION

Geo::Raster has two purposes/goals:

1) To be a general purpose tool for working with geospatial raster
data. This means "raster/map algebra" (overlaying and masking DEMs
(Digital Elevation Models), land-use rasters, etc), spatial analyses
(kriging, ...), extracting indices from the grids (histograms, ...),
etc.

2) To be a general purpose Perl/C tool for doing hydrologic and water
resources GIS work. This means watershed delineation, finding stream
networks, calculating indices (topographic index, ...), preparing data
for hydrologic models, developing spatially distributed hydrologic
modeling, etc.

Geo::Raster objects can be used as layers with Gtk2::Ex::Geo.

INSTALLATION

To install, unzip and untar the archive. In the directory created type

perl Makefile.pl
make
make test
make install

Geo::Raster requires the Raster Algebra Library libral.

Required modules are ExtUtils::Depends, Statistics::Descriptive.

Documentation is in the module file and will be added onto
perllocal.pod as usual.

ACKNOWLEDGEMENTS

array.c and array.h are taken from the Karl Glazebrook's PGPLOT
distribution.

COPYRIGHT AND LICENCE

Copyright (C) 1999- by Ari Jolma

This library is free software; you can redistribute it and/or modify
it under the terms of Artistic License 2.0 (included as LICENCE).
