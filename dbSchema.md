---
layout: page
title: Database
permalink: /onlineresources/
---

## Online Resources

There are a number of methods that can be used to access data from the Neotoma Paleoecology Database.  Users who wish to access data can use one of the following:

* Graphical Interface: The [Neotoma Explorer](http://apps.neotomadb.org/explorer)
* R Programming Language: The new [`neotoma2` R package](https://github.com/ropensci/neotoma2/). The **deprecated** [`neotoma` R package](https://github.com/ropensci/neotoma/).  Note that there are [workbooks associated with the R packages](https://open.neotomadb.org/workbooks.html) in this site that can help you get started with your research.
* Direct Web API:
  * [Neotoma API v1.5 and v2.0](http://api.neotomadb.org)
* Neotoma Programs and Applications: [The Neotoma GitHub Repository](http://github.com/neotomadb)

## Manual

The Neotoma Database is described in [online documentation hosted on Read The Docs](https://open.neotomadb.org/manual), along with SQL queries to be used directly on the database.

**Note**: We are looking for folks to help us update the Neotoma Manual.  Please contact Simon Goring ([goring@wisc.edu](mailto:goring@wisc.edu)) for more information.

## Structure

The <strong><a href="../dbschema/index.html">Neotoma Database Schema</a></strong> is generated using [SchemaSpy](http://schemaspy.org/), which provides a fully constructed HTML directory, including SVG images for tables and associated relations.

<object type="image/svg+xml" data="../dbschema/diagrams/aggregatechronologies.1degree.svg" style="display: block;margin-left: auto;margin-right: auto;width:70%; padding:5px;border-color:gray;border-style:solid;border-width:0.5px;margin-left:8px;">
  Aggregate dataset schema.
  <!-- fallback image in CSS -->
</object><br>

You can use this schema to help you build queries with Neotoma, to see what kinds of data are available from the database, to understand relationships between elements within the database and to communicate with the development team to help us support your needs.
