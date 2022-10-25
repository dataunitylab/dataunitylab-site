---
title: Challeges in Enhancing Schema Discovery of JSON Documents
event: Research Idea Ring
event_url: https://rit.zoom.us/meeting/register/tJMtceCorzoqEtL1p3uM96bg-KVLTHfYoB0n

location: Zoom

abstract: "Schema discovery is finding the structure of data. It helps users understand the meaning of data and write queries to manipulate it. This is typically easy for relational databases, but complex for non-relational (NoSQL) databases with JavaScript Object Notation (JSON) documents. JSON is a representation of documents that contain objects stored in the form of nested key-value pairs. For relational databases, the schema is predefined because the data they contain is structured, but for NoSQL databases, data is usually unstructured or semi-structured. In a collection of JSON documents, the structure of one document can be completely different from another. Several algorithms were developed to discover schemas from JSON documents, but they provide the physical structure and semantic information that is insufficient for data understanding and analysis. In this paper, we enumerate the major techniques used to extract a schema from JSON documents and present some of the next challenges that need to be addressed within the field of JSON schema discovery to enhance the quality of the discovered schemas. These challenges are (1) distinguishing when keys are data or metadata, (2) detecting frequent patterns, and (3) treating objects whose keys are semantically similar with values that are represented in different structures within nested JSON documents. We suggest methods to separate data from metadata, infer sets of new data types, and match semantically similar fields in different structures, which we call dynamic data representation."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-11-19T13:00:00-04:00
date_end: 2020-11-19T13:15:00-04:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-11-19T00:00:00-04:00

authors: ["justin-namba"]
tags: []

# Is this a featured talk? (true/false)
featured: false
---
