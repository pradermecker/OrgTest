---
author: Pierre Radermecker
title: Tasks CICD
...

Orchestration
=============

TODO Change pg~hba~ configuration<span class="tag" data-tag-name="salt"></span><span class="tag" data-tag-name="pgserver"></span>
---------------------------------------------------------------------------------------------------------------------------------

In the pgserver we need to accept all traffic from 195.244.162.100. to
allow the testing and staging saltmaster to connect.

TODO migration & support for all stacks
---------------------------------------

\[deps on projects\]

TODO Fine tunings
-----------------

TODO Add scripts
----------------

### TODO Remove certs<span class="tag" data-tag-name="salt"></span><span class="tag" data-tag-name="puppet"></span>

TODO SOP
--------

Puppet 3
========

TODO Middleware stack migration
-------------------------------

TODO Migrate all jenkins slaves<span class="tag" data-tag-name="jenkins"></span><span class="tag" data-tag-name="puppet"></span>
--------------------------------------------------------------------------------------------------------------------------------

\[deps on project\]

TODO Migrate all other stacks
-----------------------------

\[deps on projects\]

TODO SOP
--------

Support/Services
================

TODO Improve the puppet stack update process
--------------------------------------------

support CICD for "projects"
---------------------------

Update all CICD middleware to CentOS 7.2
----------------------------------------

Update the Jenkins master
-------------------------

Improve the feedback loop
=========================

TODO Replace cron with push in testing<span class="tag" data-tag-name="jenkins"></span><span class="tag" data-tag-name="salt"></span><span class="tag" data-tag-name="puppet"></span>
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### TODO in testing

### TODO in prod

TODO Improve build time<span class="tag" data-tag-name="jenkins"></span>
------------------------------------------------------------------------

GPG
===

Infrastructure to protect all sensitive configuration data (hiera)

TODO spread usage to all stacks
-------------------------------

\[deps on projects\]

Docker
======

DONE Configure registry in testing<span class="tag" data-tag-name="docker"></span>
----------------------------------------------------------------------------------

Jenkins
-------

### TODO new jobs to build images<span class="tag" data-tag-name="jenkins"></span><span class="tag" data-tag-name="docker"></span>

### TODO new specific repo to build images<span class="tag" data-tag-name="docker"></span>

### TODO Change librarian to write on disk with the local userid<span class="tag" data-tag-name="docker"></span><span class="tag" data-tag-name="puppet"></span>

TODO SOP
--------

Reporting
=========

TODO Setup and configure Foreman
--------------------------------

TODO [PostgreREST](http://postgrest.com)
----------------------------------------

VCloud API
==========

Extension des points de service via l'API

TOS usage \[Boris\]
===================

TODO Nexus
----------

TODO use puppet to setup pgpool
-------------------------------

TODO use puppet to setup Postgresql
-----------------------------------

TODO use puppet to setup Alfresco (2017 ?)
------------------------------------------
