---
title: "LDaCA Software Tools"
date: 2023-11-22T14:51:49+11:00
draft: false
description: "A variety of LDaCA open-source tools available on GitHub."
---

<br>

A variety of {{< glossary_link display="LDaCA" id="ldaca" >}} open-source tools are available at our [GitHub organisation](https://github.com/Language-Research-Technology/ocfl-js). Highlights include:

<br>

## Metadata Editor

[Crate-O](https://language-research-technology.github.io/crate-o/#/): A tool that allows you to create and update Research Object Crates ({{< glossary_link display="RO-Crates" id="ro-crate" >}}) using a web interface, and with {{< glossary_link display="metadata" id="metadata" >}} spreadsheets. It provides researchers with a relatively simple way to describe their data using the best practices in formal metadata description.

For more information about Crate-O and how to create RO-Crates with the interface, see the [Crate-O User Guide](/resources/user-guides/crate-o).

<br>

## Data Storage

[OCFL-js](https://github.com/Language-Research-Technology/ocfl-js), a library that implements the Oxford Common File Layout ([OCFL](https://ocfl.io/)): A specification for laying out digital collections on file or object storage. It is designed with long-term preservation principles in mind and does not rely on specialised software. Amongst the benefits of using {{< glossary_link display="OCFL" id="ocfl" >}} with {{< glossary_link display="RO-Crate" id="ro-crate" >}} {{< glossary_link display="objects" id="object" >}} are:

- completeness: a repository can be re-indexed from the files it stores
- versioning: repositories can make changes to objects and still allow their history to persist

<br>

## Data Portal and Access API

[Oni](https://github.com/Language-Research-Technology/oni): A web application that provides indexing, searching and access to secure data repositories following the {{< glossary_link display="Arkisto" id="arkisto" >}} model. This is used to build the [LDaCA Portal](https://data.ldaca.edu.au/search): The online interface of the Language Data Commons of Australia where users can discover and access language collections.

<br>
