---
title: NoSE
subtitle: NoSQL Schema Evaluator
summary: Automated schema design for NoSQL databases.
date: "2020-10-06:00:00Z"

links:
url_code: "https://github.com/michaelmior/NoSE.git"
url_slides: "https://speakerdeck.com/michaelmior/nose-schema-design-for-nosql-applications"

---

## Abstract

Database design is critical for high performance in relational databases and many tools exist to aid application designers in selecting an appropriate schema. While the problem of schema optimization is also highly relevant for Apache Cassandra, existing tools for relational databases are inadequate for this setting. Application designers wishing to use Cassandra instead rely on rules of thumb to select an appropriate schema. These rules can be challenging to apply without experience because they are often vague or contradictory. NoSE, an automated solution to Cassandra schema design, attempts to avoid these pitfalls.

## Introduction

NoSE is a system for recommending database schemas for Cassandra applications. Our cost-based approach uses a novel integer linear programming formulation to guide the mapping from a simple model of the application workload to a database schema

Our prototype is able to implicitly capture rules of thumb used by expert designers without explicitly encoding the rules. Automating the design process allows NoSE to produce efficient schemas and to examine more alternatives than would be possible with a manual rule-based approach.

## Rule-based Schema Design

Many experts in Cassandra data modeling have released [guidelines](http://www.datastax.com/dev/blog/basic-rules-of-cassandra-data-modeling) on how to best design schemas. These guidelines suggest that schemas should be modeled very differently from a relational database and emphasize the importance of relying on knowledge of queries which will be issued by the application.

This results in denormalization and data duplication in order to improve the performance of reads. In common deployment scenarios, writes are inexpensive in Cassandra and this denormalization results in improved performance across the entire application workload. However, when the workload becomes  complex, using a CQL table for each query can result in expensive updates and heavy storage utilization

## Automating Schema Design

To avoid the complexity of manually attempting to satisfy the conflicting requirements inherent in rule-based schema design, NoSE attempts to automate this process. This automation consists of three steps:

1. **CQL Table Enumeration**

   The schema design process starts by constructing a set of tables which are useful to answer application queries. These tables are chosen according to a simple model of query execution which uses one or more CQL tables to answer queries in the application.

2. **Query Plan Generation**

   In addition to tables enumerated in step one, NoSE assumes that some application-side logic may be necessary to answer queries. For example, if a particular CQL table returns data which is sorted incorrectly, the application may need to sort the data after it has been retrieved.

3. **Schema Selection**

   Each of the query plans in step two has an associated cost. We use these costs to construct an integer linear program (ILP) which selects a set of CQL tables to use for the final schema. The ILP implicitly explores all possible combinations of the CQL tables to find the combination which has the lowest cost.

By automating this process, NoSE is able to explore a much larger set of possible designs than a human designer. This allows the generated schema to combine results from multiple tables to answer queries. Moreover, NoSE does also not require the user to have expert knowledge of Cassandra in order to produce a good design. Armed only with a solid knowledge of the application being designed, any user should be able to produce an affective schema.
