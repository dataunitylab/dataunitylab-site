---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CoDEvo: Column family database evolution using model transformations'
subtitle: ''
summary: ''
authors:
- Pablo Suárez-Otero
- admin
- María José Suárez Cabal
- Javier Tuya
tags: []
categories: []
date: '2023-05-24'
lastmod: 2023-04-24T11:20:39+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-05-24T09:20:39.315393Z'
publication_types:
- '2'
abstract: 'In recent years, software applications have been working with NoSQL databases as they have emerged to handle big data more efficiently than traditional databases. The data models of these databases are designed to satisfy the requirements of the software application, which means that the models must evolve when the requirements of the software application change. To avoid mistakes during the design and evolution of these NoSQL models, there are several methodologies that recommend using a conceptual model. This implies that consistency between the conceptual model and the schema must be maintained when either evolving the database or the software application. In this work, we propose CoDEvo, a model-driven engineering approach that uses model transformations to address the evolution of a NoSQL column family DBMS schema when the underlying conceptual model evolves due to software requirement changes, aiming to maintain consistency between the schema and conceptual model. We have addressed this problem by defining transformation rules that determine how to evolve the schema for a specific conceptual model change. To validate these transformations, we applied them to conceptual model changes from 9 open-source software applications, comparing the output schemas from CoDEvo with the schemas that were defined in these applications.'
publication: Journal of Systems and Software
url_pdf: https://www.sciencedirect.com/science/article/pii/S0164121223001383
doi: https://doi.org/10.1016/j.jss.2023.111743
---
