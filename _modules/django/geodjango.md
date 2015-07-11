---
layout: default
title: GeoDjango 
index: 0
---

GeoDjango
============

GeoDjango is an extension for Django that leverages the most standard set of native (c/c++) spatial libraries (geos, gdal, proj4) to provide support for geometry fields in your Django models.  

Goals/Objectives/Outcomes
-------------------------

* Understand how to install GeoDjango on a specific platform
* Understand how to configure Geographic Models
* Understand how to use PostGIS databases to store spatial data attributes on models 
* Understand how to perform spatial queries using the GeoDjango ORM
* Understand how to configure the OSMGeoAdmin to display your data
* Understand how to use Geographic fields in Django forms
* Understand how to use the geos API using GeoDjango
* Understand how to use the GDAL API using GeoDjango
* Understand how to use Layer Mapping to load your spatial data into your Django model database
* Understand how to use GeoDjango Management Commands

Reference Material
------------------

* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/
* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/tutorial/
* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/admin/
* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/install/
* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/model-api/
* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/db-api/
* http://invisibleroads.com/tutorials/geodjango-googlemaps-build.html
* https://www.chicagodjango.com/blog/geo-django-quickstart/

Measures of Success
-------------------

* Participant has created a new app with a model containing Geometry fields and has demonstrated the use of those fields in the Djagno admin as well as in a form.
* Participant has loaded data from shapefiles into a PostGIS database using LayerMapping and a generated model.
* Participant has demonstrated the ability to perform basic spatial and distance lookups using the GeoQuerySet API
* Participant has demonstrated the ability to create and manipulate geometries with GEOSGeometry objects
* Participant has demonstrated the ability to work with various data sources using the GDAL API and the OGR Simple Features library
