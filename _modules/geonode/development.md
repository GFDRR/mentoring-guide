---
layout: default
title: GeoNode Development Environment 
index: 0
---

GeoNode Development Environment
===============================

If your project workplan requires that you modify GeoNode itself or you are ready to try to start fixing bugs or making modifications to the UI, you will need to create your own fork of GeoNode and clone it into your local environment and become familiar with how to work in a branch, track the changes in master and eventually send a Pull Request that the GeoNode core developers can review and merge.

Once your development environment is setup, your Mentor will guide you through the process of determining the best strategy for making the required modifications to GeoNode and through submitting a Pull Request and the review and merge process. You can review the section on Git and GitHub above if you need some guidance on how to work with forks and branches of a repository both in your local environment and using GitHub as a remote. 

You should also be comfortable working in your local development environment and with virtualized environments whether locally or on the cloud. The section on Python Development above has many pointers on the basic development tools used in geonode and other pointers on how to setup your development environment to your liking. You can reference the section on Virtualization above. When you are ready, you will deploy your modifications to a server for testing and solicit feedback from your Mentor and the wider community and your project stakeholders. Reference the sections on Internet Infrastructure and Web Servers above when you are ready to launch your service in Alpha. You can test the Pull Request workflow by making small changes to the documentation (see Documentation) or other non intrusive places in the codebase. 

Your mentor will guide you through this process and when you have mastered it, you are well on your way to being a GeoNode core contributor and should be beginning to offer help to others in the community and work toward becoming a Mentor yourself. When you have truly Mastered these skills, you can begin the process of learning how to automate your deployments using DevOps techniques and methodology. Your mentor may also recommend that you begin to look at other areas of the Open Source DRM stack that might be applicable for your project. 

Goals/Objectives/Outcomes
-------------------------

* Understand the install process for the pre-requisites necessary to set up a GeoNode development environment
* Understand how to fork GeoNode to another GitHub user or organization account and how to clone this fork locally and setup GeoNode master upstream as a remote
* Understand how to use paver to install all of the GeoNode components locally
* Understand how to start, stop and reset the GeoNode development server
* Understand how to deploy a modified local copy of GeoNode
* Understand how to use the secondary paver tasks to perform other common development tasks
* Understand how to load sample data into the GeoNode development environment
* Understand how to run the GeoNode test suites
* Understand how to work in a local branch of GeoNode
* Understand how to Push changes from a local branch to the a fork of GeoNode master on GitHub
* Understand how to send a Pull Request against GeoNode Master

Reference Material
------------------

* http://geonode.readthedocs.org/en/latest/tutorials/devel/envsetup/index.html
* https://help.github.com/articles/using-pull-requests/
* https://help.github.com/articles/creating-a-pull-request/
* https://help.github.com/articles/fork-a-repo/
* http://yangsu.github.io/pull-request-tutorial/
* https://docs.djangoproject.com/en/1.7/howto/deployment/
* https://www.digitalocean.com/community/tutorials/how-to-deploy-a-local-django-app-to-a-vps
* http://www.djangobook.com/en/2.0/chapter12.html
* http://stackoverflow.com/questions/26871381/deploying-a-local-django-app-using-openshift

Measures of Success
-------------------

* Participant has a working GeoNode development environment
* Participant has demonstrated the ability to work with the paver common paver tasks
* Participant has demonstrated the ability to work with sample data or bulk load other data into their development environment
* Participant has demonstrated the ability to run the GeoNode test suites
* Participant has deployed their fork and branch of GeoNode to a server for testing
* Participant has created a fork of GeoNode in their own account and cloned this fork into their own local environment and is comfortable working in a branch and with remotes
* Participant has sent a Pull Request against GeoNode master
