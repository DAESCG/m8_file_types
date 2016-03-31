m8_file_types
=============

This repository houses all relevant content for the 8th DAES CG meeting, held
on Thursday, 24 March 2016.

Announcements
-------------
**The next meeting will be held on Thursday, 14 April 2016 unless otherwise
noted.**

Meeting Synopsis
----------------
The 8th DAES CG meeting covered commonly used data formats in the atmospheric and
climate science communities. These formats include GRIB, NetCDF, HDF, and more
recently, JSON.

The first half of the meeting was spent discussing the primary conventions and
uses of GRIB and NetCDF files. HDF and JSON file usage was then discussed at length,
and a GeoJSON demonstration using the [d3](http://d3js.org) JavaScript library
was provided.

Contents
--------
1. `README.md`                  | Master README file
2. `BigDataSupplemental.pdf`    | An overview of data formats, including GRIB and NetCDF
3. `examples/places.json`       | A GeoJSON file containing populated place names/coordinates
4. `examples/sub_units.json`    | A GeoJSON file containing sub domain information
5. `examples/uk.json`           | A GeoJSON file containing UK topological data
6. `examples/uk_map.html`       | An HTML file that joins GeoJSON data with the d3 JS library.

Useful Links
------------
1. [d3 JavaScript Library](http://d3js.org)
2. [GeoJSON Documentation](http://geojson.org)
3. [Python netCDF4 Module](http://unidata.github.io/netcdf4-python/)
4. [Python h5py Module](http://docs.h5py.org/en/latest/)

Installation
------------
```
git clone https://github.com/DAESCG/m8_file_types
```
