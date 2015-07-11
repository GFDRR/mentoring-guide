---
layout: default
title: Django Management Commands 
index: 0
---

Django Management Commands
===========================

Django Management commands provide the ability to run common administration tasks using a script on the command line. Several commonlly used management commands such as syncdb, createsuperuser, migrate or runserver may already be familiar to you. Mastering this set of commands is key to being able to run a Django applicationin production. Eventually, you will want to learn how to write your own management commands in your own django apps and there are established best practices that should be followed.

Goals/Objectives/Outcomes
-------------------------

* Understand how to use the full range of standard Django Management commands to perform common administrative tasks
* Understand how to use database migrations
* Understand how to use django.contrib.auth commands to manage users and set passwords
* Understand how to use the ping_google management command
* Understand how to use the collectstatic management command
* Understand the set of available GeoNode management commands (importlayers, updatelayers)
* Understand how to use the ogrinspect management command
* Understand how to create a new management command in a django app

Reference Material
------------------

* https://docs.djangoproject.com/en/1.8/ref/django-admin/
* https://docs.djangoproject.com/en/1.8/ref/contrib/gis/commands/
* https://docs.djangoproject.com/en/1.8/howto/custom-management-commands/
* http://geonode.readthedocs.org/en/latest/tutorials/admin/commands.html
* https://docs.djangoproject.com/en/1.8/topics/migrations/

Measures of Success
-------------------

* Participant has demonstrated the ability to use manage a server using common Django management commands
* Participant has demonstrated to perform basic database migrations using model changes
* Participant has configured sitemaps for their site and notified google search of their site using ping_google command
* Participant has demonstrated the ability to manage static resources using collectstatic
* Participant has demonstrated the ability to import data to a GeoNode using importlayers or updatelayers
* Participant has demonstrated the ability to inspect an existing PostGIS table using ogrinspect
* Participant has created their own custom management command in their own app
