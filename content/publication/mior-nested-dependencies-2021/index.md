---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fast Discovery of Nested Dependencies on JSON Data"
authors: ["admin"]
date: 2021-11-19T00:00:00-04:00

# Schedule page publish date (NOT publication's date).
publishDate: 2021-11-19T00:00:10-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Computing Research Repository"

abstract: "Functional and inclusion dependencies are the most widely used classes of data dependencies in data profiling due to their ability to identify relationships in data such as primary and foreign keys. These relationships are equally important when dealing with nested data formats such as JSON. However, the definition of functional and inclusion dependencies makes use of a flat, unnested relational model which misses many useful types of dependencies on data which involve nested data models.
In this work, we identify types of dependencies which are not captured by traditional functional and inclusion dependencies but which nevertheless capture meaningful relationships among nested data. We also demonstrate how algorithms for mining these traditional dependencies can be adapted to also mine nested dependencies. The first strategy simply flattens the input data and feeds into unmodified existing algorithms. We present a second strategy which instead adapts the algorithm to efficiently process JSON data as input which in some cases leads to a reduction in runtime by multiple orders of magnitude on real-world datasets. We further show how these algorithms can be adapted to produce useful results in the presence of a percentage of incomplete or invalid data."

summary: "Discovery of nested data dependencies on semi-structured data sources."

tags: []
categories: []
featured: true

url_pdf: https://arxiv.org/pdf/2111.10398.pdf

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
