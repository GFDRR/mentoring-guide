---
layout: default
title: Spatial Indexes 
index: 0
---

Spatial Indexes
===============

Spatial indexes are used in PostGIS to speed up queries. It is essential to understand how to create and manage spatial indexes on your databases in order to avoid slow sequential queries that scan every record in a table. Indexing speeds up searches by organizing the data into trees that can be quickly traversed to find specific records. PostGIS supports 3 type of indexes (B-Tree, R-Tree and GIST). GIST are the most commonly used types of indexes.  

Goals/Objectives/Outcomes
-------------------------

* Understand why indexes are used to improve search/query performance
* Understand how to create and manage indexes on your spatial data tables
* Understand how to construct queries that make the best use of indexes

Reference Material
------------------

* http://revenant.ca/www/postgis/workshop/indexing.html
* http://postgis.net/docs/using_postgis_dbmanagement.html#idp7256064
* http://suite.opengeo.org/4.1/dataadmin/pgBasics/indexes.html
* http://workshops.boundlessgeo.com/postgis-intro/indexing.html

Measures of Success
-------------------

* Participant can articulate the purpose of spatial indexes and how they work
* Participant has successfully added indexes to tables containing spatial data in their database
* Participant has demonstrated the ability to leverage indexes properly when constructing queries
