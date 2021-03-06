---
title: Quick Overview
description: Nuxeo Platform is a set of server and client side software artifacts and tools that allow you to build, operate and maintain advanced content management applications.
review:
    comment: ''
    date: '2019-11-26'
    status: ok
labels:
    - lts2016-ok
    - architecture
    - fguillaume
    - overview
    - lts2017-ok
toc: true
notes: Documentation page used by the Marketing team. Check with Marketing before deleting or moving.
confluence:
    ajs-parent-page-id: '7209076'
    ajs-parent-page-title: Tutorials
    ajs-space-key: NXDOC
    ajs-space-name: Nuxeo Platform Developer Documentation
    canonical: Quick+Overview
    canonical_source: 'https://doc.nuxeo.com/display/NXDOC/Quick+Overview'
    page_id: '18451470'
    shortlink: DowZAQ
    shortlink_source: 'https://doc.nuxeo.com/x/DowZAQ'
    source_link: /display/NXDOC/Quick+Overview
tree_item_index: 50
history:
    -
        author: Alain Escaffre
        date: '2015-10-13 14:46'
        message: ''
        version: '17'
    -
        author: Solen Guitter
        date: '2015-04-09 08:06'
        message: make video responsive
        version: '16'
    -
        author: Solen Guitter
        date: '2014-12-03 14:20'
        message: ''
        version: '15'
    -
        author: Alain Escaffre
        date: '2014-09-29 14:47'
        message: ''
        version: '14'
    -
        author: Bob Canaway
        date: '2014-09-24 03:53'
        message: ''
        version: '13'
    -
        author: Bob Canaway
        date: '2014-09-24 03:53'
        message: ''
        version: '12'
    -
        author: Solen Guitter
        date: '2014-09-19 14:58'
        message: ''
        version: '11'
    -
        author: Thibaud Arguillere
        date: '2014-03-25 16:32'
        message: ''
        version: '10'
    -
        author: Solen Guitter
        date: '2014-03-21 13:51'
        message: ''
        version: '9'
    -
        author: Thierry Delprat
        date: '2014-03-21 12:41'
        message: ''
        version: '8'
    -
        author: Thierry Delprat
        date: '2014-03-21 12:40'
        message: ''
        version: '7'
    -
        author: Solen Guitter
        date: '2014-03-21 12:05'
        message: ''
        version: '6'
    -
        author: Solen Guitter
        date: '2014-03-21 12:05'
        message: ''
        version: '5'
    -
        author: Thierry Delprat
        date: '2014-03-21 11:52'
        message: ''
        version: '4'
    -
        author: Thierry Delprat
        date: '2014-03-21 11:27'
        message: ''
        version: '3'
    -
        author: Thierry Delprat
        date: '2014-03-21 11:17'
        message: ''
        version: '2'
    -
        author: Thierry Delprat
        date: '2014-03-21 11:02'
        message: ''
        version: '1'
---

## What is Nuxeo Platform

Nuxeo Platform is a set of server and client-side software artifacts and tools that allow you to build, operate and maintain advanced content management applications: core business applications with strong DAM or Case Management flavors, verticalized document management systems, hyperscale archival repositories and more. Among all the reasons why you would like to use Nuxeo Platform for your project, the most obvious are:

- A proven track of **reached performances** goals

- A **state of the art technical design** and software engineering tooling

- **Advanced content repository, workflow and content transformation** features

- An **open development model** with great documentation and great visibility on product evolutions that enables you to reach a high level of expertise quickly


Main components of the Nuxeo Platform are:

- **[Nuxeo Server]({{page version='' space='nxdoc' page='nuxeo-server'}})**, that runs on top of the Java Virtual Machine, with different deployment options. The Nuxeo Server exposes a modular set of features via a REST API. The Nuxeo Package system allows to define what bundles are deployed on the Nuxeo Server easily. Nuxeo Server is often called Nuxeo Platform as a shortcut, and because it is the most important asset of the Nuxeo Platform, embedding a fully-featured repository, a content transformation grid and a workflow engine. The Nuxeo Server is [benchmarked](https://benchmarks.nuxeo.com) continuously to guarantee performance expectations

- **[Nuxeo Web UI]({{page version='' space='nxdoc' page='web-ui'}})**: a flexible and pluggable content browser that allows users to perform usual content management operations in a highly productive style: browse, search, upload, preview, download, resolve tasks, etc. Web UI's strength is its capability of being heavily customized for taking into account your application's data model and custom business process.

- **[Nuxeo Addons]({{page version='' space='nxdoc' page='nuxeo-add-ons'}})**: as we said above, you can install additional bundles on top of the bare Nuxeo server to enrich its features and capabilities set. Nuxeo Addons compatible with a given version of the Nuxeo Server are distributed through the Nuxeo Marketplace.

- **[Client SDKs]({{page version='' space='nxdoc' page='client-sdks'}})** and **[Nuxeo Elements]({{page version='' space='nxdoc' page='nuxeo-elements'}})**: Java, JavaScript, C#, Python, PHP, iOS, DART: several clients are available to quickly start integrating with Nuxeo Server without having to know the details of our REST API. We even provide a rich set of web components, the "Nuxeo Elements" that brings out-of-the-box features that you can include in your application just by using the good HTML tag.

- **[Nuxeo Drive]({{page version='' space='client-apps' page='nuxeo-drive'}})**: a desktop application that maps a Nuxeo repository's content to a Desktop's file system, with synchronization logics and offline access and edit capabilities, in the spirit of Enterprise File Sharing Systems like Dropbox or Box.

- **[Nuxeo Mobile]({{page version='' space='client-apps' page='nuxeo-mobile'}})**: Native Android and iOS applications developed with React Native and available on respective stores. A React Native framework to build custom mobile applications is being developed and will be released later in the year 2017.

- **[Build, QA and Performance analysis tooling]({{page version='' space='corg' page='development-tools-and-process'}})**: All the tooling we use for building, maintaining and testing our software artifacts is free and open source. It is available for your own project, as a great catalyzer of your engineering practices.

- **[Nuxeo Studio]({{page version='' space='studio' page='nuxeo-studio'}})** and **[Nuxeo CLI]({{page version='' space='nxdoc' page='nuxeo-cli'}})**: Nuxeo Studio is an online application to implement project's customization requirements quickly: content modelling, business logic and user interface design. Nuxeo Studio is much more than a rapid application development tool: it guarantees that your customization will be maintained automatically throughout the future releases of Nuxeo Platform components. Nuxeo CLI is a command-line tool for helping developers bootstrap their custom modules.

- Additional **[Client Integrations]({{page version='' space='nxdoc' page='nuxeo-add-ons'}})**: Some additional client integrations are available: Adobe CC, Salesforce, Aspera, Sitecore and more.

- **PaaS** and **Docker Deployment**: Tooling </br>
Nuxeo has strong expertise in deploying Nuxeo Platform instances on docker containers, PaaS style, which you typically want to do if you are building a vertical application on top of Nuxeo and have multi-tenancy considerations.

## Turnkey Application and Headless Repository

You may be interested in using the Nuxeo Platform for your project for different use cases:
- If you need a headless scalable document repository with rich APIs and data structures.
- If you need a turnkey application for managing assets (description, validation, publishing) with still the ability to customize it strongly.
- If you want to build a custom UI upon the repository and want to benefit from our rich library of UI elements to accelerate the development of your project.

## Technical Overview

### Languages and Configuration / Customization Principles

All server parts of Nuxeo, including plugins, are written in Java, with a mechanism of bundles and components for packaging developments. The Web UI (the customizable client web application) is written in JavaScript (using the Polymer framework). Default application can be configured using Nuxeo Studio, an online development environment.  It is also possible to write Java plugins.

### Deployment

Nuxeo Server comes bundled with a Tomcat server. It requires for production to set up several other components: Elasticsearch, Redis, a relational (SQL) database or NoSQL store (like MongoDB). Deployment options support HA, failover and can be on-premise, or in the cloud, on bare machines, virtual machines or Docker containers. For more details about the Nuxeo deployment system, please refer to [pages on Standard High Availability Nuxeo Cluster Architecture]({{page page='standard-high-availability-nuxeo-cluster-architecture'}}).
Nuxeo bundles can even be started on a JVM directly (i.e. without an application server). This is the deployment mode in all unit tests.

## About Nuxeo Platform Data

Data managed by the Nuxeo Platform includes:

- Documents:
    - Metadata
    - Binary files
- Users, Groups
- Reference data
- Indexes

### Document Repository

The Nuxeo Document repository focuses on managing Document persistence.

It covers:

- Hierarchy definition
- Security descriptors
- Metadata
- Binaries
- Indexes

The default configuration for Nuxeo Repository is to use a SQL Database and Filesystem storage, as well as an Elasticsearch index (that can be removed from the architecture if necessary):

* To manage hierarchy, security and metadata, the Nuxeo repository provides a generic Java interface with two implementations: [VCS]({{page page='VCS'}}) that integrates with SQL databases, or [DBS]({{page page='DBS'}}) that integrates with NoSQL databases. You can easily configure the backend of your choice, among MongoDB, PostgreSQL, Oracle, MySQL, MariaDB, Microsoft SQL Server and MarkLogic. Implementing a new relational or document backend, if needed, is straightforward.

- Binaries streams are stored in an _"Object Store like"_ storage called "BlobProvider". Many implementations are provided out of the box (File System, S3, Azure Blob Storage, JCloud, Google Drive, Dropbox and more) and it is straightforward to add a new implementation.

For more details about Nuxeo Repository and BlobStore, please see the page [File Storage]({{page page='file-storage'}}).

The following schema shows main persisted and indexed data on a typical Nuxeo setup.
![]({{file name='global-architecture.png'}} ?w=600, border=true)

### Indexes

The standard setup of Nuxeo Platform includes using an Elasticsearch index used in most of the queries made in the application. Yet the repository can be deployed and used without those additional Elasticsearch indexes. VCS implementation even natively includes a full-text search.

### Non Document Data

Nuxeo uses an abstraction called Directory system that allows addressing Data in SQL, LDAP (or WebService).
The Directories are typically used for storing:

- Users
- Groups
- Lists of controlled values

By default, everything is bound to the same SQL database as the repository, but you can choose:

- To bind some directories to LDAP
- To bind some directories to an external SQL database

![]({{file name='DirectoryAbstraction.png'}} ?w=650,border=true)

## Integrating Nuxeo

### Calling Nuxeo Services

Nuxeo resources (Documents, Users, Tasks ...) are exposed via a [REST API]({{page page='rest-api'}}).
Nuxeo services are exposed via an HTTP API called [Nuxeo Automation]({{page page='content-automation-concepts'}}).

So, if your external application needs to call the Nuxeo Server, you can use plain HTTP/JSON API to do the calls, or you can use one of the[ client libraries]({{page page='client-sdks'}}) we provide.

![]({{file name='EndPoints.png'}} ?w=650,border=true)

### Calling External Services from the Nuxeo Server

You can extend the Nuxeo Platform to deploy your own Java Services.
A standard approach is to wrap your calls to external applications inside a [Nuxeo Automation Operation]({{page page='contributing-an-operation'}}) (or, even better, inside a Nuxeo Service wrapped in an Automation operation). Once you have this operation, you can use it Nuxeo Studio for deep integration in your business processes:

- Use it inside a Workflow.
- Bind the call to the external service on new buttons in the UI.
- Associate your external service operation with events happening inside the repository.

![]({{file name='EventBus.png'}} ?w=500,border=true)

### Data Integration

In addition of the native HTTP API, the Nuxeo Platform also provides solutions to [import data inside the Nuxeo Platform]({{page page='choosing-how-to-import-data-in-the-nuxeo-platform'}}).


## Customizing the Web UI

The Web UI is written on top of the Web Components standard and the paradigms of the Polymer Framework.
