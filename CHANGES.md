## Version 1.2.10 on 1 March 2019

Fix incorrect query of astropy version information to deal with
deprecation of ``_naxis1`` and ``_naxis2`` WCS attributes. [#165]


## Version 1.2.9 on 22 February 2019

Fixed a bug introduced in version ``1.2.8``


## Version 1.2.8 on 22 February 2019

Add backwards compatibility with Astropy 3.1.0

`<3.1.0` uses `wcs._naxis`
`>=3.1.0` uses `wcs.pixel_shape`


## Version 1.2.7 on 14 November 2018

Restored _naxis, pixel_shape not ready yet≈ß


## Version 1.2.6 on 13 November 2018

Replaced _naxis with pixel_shape

Updated README file

Removed debugging code from graph.py

## Version 1.2.5 on 10 July 2018

Added a method to create a polygon from the convex hull of a list
of points.

## Version 1.2.4 on 28 June 2018

The public methods in SingleSphericalPolygon now match the methods in
SphericalPolygon so that objects of either type can be used
interchangably (for the most part.) SphericalPolygon now subclasses
SingleSphericalPolygon.

## Version 1.2.3 on 20 June 2018

Every method with lonlat in its name now has an alias with lonlat
replaced by radec.

The class _SingleSphericalPolygon has been renamed to
SingleSphericalPolygon. The former name has been retained as an alias.

The from_lonlat (and from_radec) method is now available in
SingleSphericalPolygon as well as SphericalPolygon.

The methods iter_polygons_flat have been renamed to to __iter__. The
former name has been retained as an alias.
