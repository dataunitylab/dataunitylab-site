---
title: Column-Oriented Database Application Evolution Using Conceptual Models
event: Research Idea Ring
event_url: https://www.cs.rochester.edu/dept/seminar/view/dept/2019/12/16/1303/Michael_Mior/Fast_Discovery_of_Nested_Dependencies_on_JSON_Data.html

abstract: "Schema design for NoSQL column-oriented database applications follows a query-driven strategy where each table satisfies a query that will be executed by the client application. This strategy usually implies that the schema is denormalized, as the same information can be queried several times in different ways, leading to data duplication in the database. Because the schema does not provide information such as where the data is duplicated or the relationships between conceptual entities, developers must use additional information when evolving the database. One strategy for accessing this information is to use a conceptual model that must be synchronized and kept consistent with the physical schema. In this work, we propose a column-oriented database application evolution framework that consists of four sequential stages: 1) Reflect the schema change in the conceptual model. 2) Take the necessary actions in the schema to maintain consistency between the new conceptual model and the schema 3) Maintain data integrity through migration of data. 4) update and adapt the client application to the new schema."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-04-07T13:00:00-04:00
date_end: 2022-04-07T13:15:00-04:00
#date_end: 2020-12-16T13:00:00-04:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2022-04-07T00:00:00-04:00

authors: ["pablo-suarez-otero"]
tags: []

# Is this a featured talk? (true/false)
featured: true
---
