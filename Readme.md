## Introduction

SeaTable is an online lightweight database with a spreadsheet interface. It helps you to easily record and manage all kinds of scattered information. With APIs and SDKs, you can quickly scale to your needs, automate data processing and automate business processes.

Main features includes:

* A spreadsheet like interface to records data supporting collaboratively editing.
* A form app to collect data
* Mobile ready UI to be used on browsers in mobile system
* Comprehensive API and SDK to add **UI Plugins** and **background scripts** for your SeaTable
* Filters, sorts, charts and pivot tables to visualize and analyze data.

## History

SeaTable is originally built by the Seafile team (https://github.com/haiwen/seafile). The idea was to add online collaboration table feature to Seafile. Later it involved into a separate project. The business is now moved to SeaTable GmbH.

## Repositories

General

* [Scripts examples](https://github.com/seatable/seatable-scripts-examples): Example background scripts that you can add to extend SeaTable.
* [Plugin template](https://github.com/seatable/seatable-plugin-template): The template for writing your own UI plugin.

Plugins

* [Timeline plugin](https://github.com/seatable/seatable-plugin-timeline): Show records in timeline.


## Software components

SeaTable consists of following components

* dtable-web: The web site for manage tables.
* dtable-server: Store the tables and provide collaborating feature.
* [dtable-events](https://github.com/seatable/dtable-events): Background maintenance tasks
* [seaf-server](https://github.com/haiwen/seafile): Store attachments (files and images)
* [ccnet-server](https://github.com/haiwen/ccnet-server): Will be removed later.

## LICENSE

The different components of SeaTable community edition are released under different licenses:

* dtable-web: Apache License v2
* dtable-events: Apache License v2
* dtable-server: Proprietary License
* seaf-server: AGPLv3

Note:

* The source code will be uploaded to GitHub later. They are currently included in the Docker image if you are interested.

## Reporting issues

Please report issues in the forum: https://forum.seatable.io/

