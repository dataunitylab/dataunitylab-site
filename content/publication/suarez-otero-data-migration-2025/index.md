---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Data migration for column family database evolution'
subtitle: ''
summary: ''
authors:
- Pablo Suárez-Otero
- admin
- María José Suárez Cabal
- Javier Tuya
tags: []
categories: []
date: '2025-11-01'
lastmod: 2025-08-20T07:09:39+02:00
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
publishDate: '2025-08-20T07:09:39.315393Z'
publication_types:
- '2'
abstract: "Context: Database evolution involves processes such as the evolution of the schema, the adaptation of the application to the new schema, and migrations of data to the new or modified structures of the schema. Data migration is particularly crucial in databases where data repetition is common such as the NoSQL column family DBMSs. In these systems, data integrity cannot be enforced from the database side, but instead needs to be maintained from the application side. Database evolution is also affected by data repetition and the absence of data integrity enforcement from the database, as any evolution of the schema requires data migrations to maintain data integrity.\nObjectives: Ensure data integrity in NoSQL column family DBMSs during database evolution by providing specific instructions for the execution of the necessary data migrations.\nMethods: We propose MoDEvo, a model-driven engineering approach that provides a data migration model to ensure data integrity for database evolution in column-family DBMSs. This model is then transformed into an executable script that implements the migration procedures.\nResults: We evaluate MoDEvo by executing data migrations in case studies obtained from open-source projects where the schema evolved. In this evaluation we use Apache Cassandra, the most popular column-family DBMS. Through this evaluation, we verify that the scripts generated from the data migration model effectively maintain data integrity within the database.\nConclusion: MoDEvo aids database evolution in column family DBMSs by avoiding the incurrence in the creation of inconsistencies and can also detect impossible migrations, thereby preventing errors. There is still room for improvement such as extending the supported databases to other paradigms where data repetition is common and addressing the evolution of the client applications alongside schema evolution."
publication: Information and Software Technology
url_pdf: https://www.sciencedirect.com/science/article/pii/S0950584925001739
doi: https://doi.org/10.1016/j.infsof.2025.107834
---
