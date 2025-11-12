## Introduction

SeaTable is a spreadsheet/database like Airtable. The initial idea is for people to manage different kinds of data in a single platform. With built-in automation rules, scripts and APIs, you can automate data processing with no code or little code.

The core features include:

* A spreadsheet like interface supporting collaboratively editing
* Mobile ready UI to be used on browsers in mobile system
* Unlimited rows in a single base
* Interconnect data between bases
* Automate data processing without coding
* Powerful APIs as well as SQL interface
* self-hosted, no restriction on API calls

## History

SeaTable is originally built by the Seafile team (https://github.com/haiwen/seafile). The idea was to add online collaboration table feature to Seafile. Later it involved into a separate project. The business is now moved to SeaTable GmbH.

## How to install SeaTable

Please check our manual: https://admin.seatable.com

## Repositories

General

* [Admin Manual](https://github.com/seatable/seatable-admin-docs): Official SeaTable Admin Manual
* [OpenAPI Defintion](https://github.com/seatable/openapi): OpenAPI Specification for the SeaTable API

Plugins

* [Timeline plugin](https://github.com/seatable/seatable-plugin-timeline): Show records in timeline.
* [Map](https://github.com/seatable/seatable-plugin-map): Show records in Google Map. 
* [Deduplicate](https://github.com/seatable/seatable-plugin-deduplicate): Detect duplicated records.
* [Tree](https://github.com/seatable/seatable-plugin-tree)
* ... many more ...


## Software components

SeaTable consists of following components

* dtable-web: The web site for manage tables.
* dtable-server: Store the tables and provide collaborating feature.
* [dtable-events](https://github.com/seatable/dtable-events): Background maintenance tasks
* [seaf-server](https://github.com/haiwen/seafile): Store attachments (files and images)
* [thumbnail-server](https://github.com/seatable/seatable-thumbnail-server): serve image thumbnail and other static contents

## LICENSE

The different components of SeaTable community edition are released under different licenses:

* dtable-web: Apache License v2
* dtable-events: Apache License v2
* dtable-server: Proprietary License
* seaf-server: AGPLv3
* thumbnail-server: Apache License v2

Note:

* The source code will be uploaded to GitHub later. They are currently included in the Docker image if you are interested.

## Reporting issues

Please report issues in the forum: https://forum.seatable.com/

