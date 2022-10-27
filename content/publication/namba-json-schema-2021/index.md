---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Enhancing JSON Schema Discovery by Uncovering Hidden Data"
authors: ["justin-namba"]
date: 2021-08-16T00:00:00-04:00

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-16T00:00:10-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "VLDB PhD Workshop"

abstract: "Schema discovery is finding the structure of data. It helps users understand the meaning of data and write queries to manipulate it. This is typically easy for relational databases, but complex for non-relational (NoSQL) databases with JavaScript Object Notation (JSON) documents. JSON is a representation of documents that contain objects stored in the form of nested key-value pairs. For relational databases, the schema is predefined because the data they contain is structured, but for NoSQL databases, data is usually unstructured or semi-structured. In a collection of JSON documents, the structure of one document can be completely different from another. Several algorithms were developed to discover schemas from JSON documents, but they provide the physical structure and semantic information that is insufficient for data understanding and analysis. In this paper, we enumerate the major techniques used to extract a schema from JSON documents and present the next challenge: uncovering hidden data disguised as metadata. This challenge needs to be addressed within the field of JSON schema discovery to enhance the quality of the discovered schemas."

summary: "Improving JSON schema discovery by disambiguating metadata."

tags: []
categories: []
featured: true

url_slides: "https://vldb.org/2021/files/slides/phd/JustinNamba.pdf"

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["json-schema-inference"]
---
