---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "NoSE: Schema Design for NoSQL Applications"
authors: ["admin", "Kenneth Salem", "Ashraf Aboulnaga", "Rui Liu"]
date: 2017-07-03T00:00:00-04:00
doi: "10.1109/TKDE.2017.2722412"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-06T18:05:15-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Transactions on Knowledge and Data Engineering"
publication_short: "TKDE"

abstract: "Database design is critical for high performance in relational databases and a myriad of tools exist to aid application designers in selecting an appropriate schema. While the problem of schema optimization is also highly relevant for NoSQL databases, existing tools for relational databases are inadequate in that setting. Application designers wishing to use a NoSQL database instead rely on rules of thumb to select an appropriate schema. We present a system for recommending database schemas for NoSQL applications. Our cost-based approach uses a novel binary integer programming formulation to guide the mapping from the application's conceptual data model to a database schema. We implemented a prototype of this approach for the Cassandra extensible record store. Our prototype, the NoSQL Schema Evaluator (NoSE) is able to capture rules of thumb used by expert designers without explicitly encoding the rules. Automating the design process allows NoSE to produce efficient schemas and to examine more alternatives than would be possible with a manual rule-based approach."

# Summary. An optional shortened abstract.
summary: "Automated schema design for NoSQL databases."

tags: []
categories: []
featured: false

url_code: "https://github.com/michaelmior/NoSE.git"

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["nose"]
---
