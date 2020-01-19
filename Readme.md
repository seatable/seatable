## Introduction

SeaTable is an online lightweight database with a spreadsheet interface. It helps you to easily record and manage all kinds of scattered information. With APIs and SDKs, you can quickly scale to your needs, automate data processing and automate business processes.

Main features includes:

* A spreadsheet like interface to records data supporting collaboratively editing.
* A form app to collect data from outside.
* Mobile ready UI to be used on browsers in mobile system to view and collect data.
* Comprehensive API and SDK for adding extensions.
* Filters, sorts, charts and pivotal tables to visualize and analyze data.

## History

SeaTable is build by the Seafile team (https://github.com/haiwen/seafile). The original idea was to add online collabration table feature to Seafile. Later it involved into a seperate project.

## Software components

SeaTable consists of following component

* dtable-web: The web site for manage tables.
* dtable-server: Store the tables and provide collaborating feature.
* dtable-events: Background maintenance tasks
* seaf-server: Store attachments (files and images)
* ccnet-server: Will be removed later.

## LICENSE

The different components of SeaTable community edition are released under different licenses:

* dtable-web: Apache License v2
* dtable-events: Apache License v2
* dtable-server: Proprietary License
* seaf-server: AGPLv3

Note:

* The source code will be uploaded to GitHub later. They are currently included in the Docker image if you are interested.

## Reporting issues

Please report bugs related to SeaTable community edition at https://github.com/seatable/seatable/issues
