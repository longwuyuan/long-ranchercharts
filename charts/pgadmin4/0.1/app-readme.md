# pgAdmin

pgAdmin is the most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.
## Prerequisites

- Kubernetes 1.6+ with Beta APIs enabled

## Introduction

This chart is built on the hub.docker.com image dpage/pgadmin4.
The default username to login is admin@localhost. You can change it in your answer during install.
The default password is "admin". You can change it in your answer during install.

You can visit http://www.pgadmin.org to know more.


## Installing the Chart

Change the username and password if you don't want to use the defaults.

This chart does not expose pgadmin4 outside the cluster.

Use the loadbalancing tab to create a ingress to the ClusterIP service created by this chart.

