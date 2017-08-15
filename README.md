Rocana Fork
===========

This is a fork of [cloudera/cm_api](https://github.com/cloudera/cm_api).

The fork was originally performed to get around an issue that may be resolved in https://github.com/cloudera/cm_api/pull/63.
This fork may no longer be needed once that has merged, and another release of the original repo is made.

Cloudera Manager RESTful API Clients
====================================

> [Cloudera Manager](http://www.cloudera.com/products-services/tools/) is the market-leading management platform 
> for [CDH](http://www.cloudera.com/hadoop/). As the industry’s first end-to-end 
> management application for Apache Hadoop, Cloudera Manager sets the standard for enterprise deployment by 
> delivering granular visibility into and control over every part of CDH – empowering operators to improve 
> cluster performance, enhance quality of service, increase compliance and reduce administrative costs.

This project contains all the source, examples and documentation 
you need to easily build a [Cloudera Manager](http://www.cloudera.com/products-services/tools/) client in 
[Java](java) or [Python](python).

All source in this repository is [Apache-Licensed](LICENSE.txt).

This client code allows you to interact with Cloudera Manager to:
* Manage multiple clusters
* Start and stop all or individual services or roles
* Upgrade services running on your cluster
* Access time-series data on resource utilitization for any activity in the system
* Read logs for all processes in the system as well as stdout and stderr
* Programmatically configure all aspects of your deployment
* Collect diagnostic data to aid in debugging issues
* Run distributed commands to manage auto-failover, host decommissioning and more
* View all events and alerts that have occurred in the system
* Add and remove users from the system
