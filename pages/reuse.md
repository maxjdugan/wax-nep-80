---
layout: page
title: Reuse the Collection
permalink: /reuse/
collection: nep_80
---
Like [Wax minicomp](https://minicomp.github.io/wiki/), this project aspires to make its archive accessible, interoperable, and reusable in accordance with [FAIR data principles](https://journal.code4lib.org/articles/13427)


The demo site comes with a specific `_include` called `interactive_metadata_table` to help you make pages like this one complete with interactive [DataTables](https://datatables.net/) and downloadable CSVs of collection metadata.

{% include interactive_metadata_table.html collection=page.collection %}
