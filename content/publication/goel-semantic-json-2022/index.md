---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Semantic JSON Generation"
authors: ["chirag-goel"]
date: 2022-05-31T00:00:00-04:00

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-31T00:00:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

abstract: "Semantic types describe the information about the entity types and the data those types hold. Detecting semantic types has been a challenge in recent years, and most machine learning models fail to detect semantic types with great accuracy when used against dirty data. These models were generally trained on relational databases, and the testing results of models trained on JSON datasets are still unknown. I introduce a way of creating JSON data files that can be used for training the models that can detect semantic types. I used the sherlock dataset to create JSON data files based on the relationships found amongst the semantic types. The relationships between the semantic types were determined using the ontology mentioned on DBpedia. I was able to find different types of relationships between the semantic types, and based on those relationships I was able to generate Semantic JSON data files. However, I found some anomalies corresponding to some semantic types in the final JSON data files. To evaluate the results, I tracked the anomalies from the sherlock dataset to the source dataset. The source dataset was corrupted at the time sherlock dataset was created."

url_pdf: uploads/publications/Goel2022.pdf

tags: []
categories: []
featured: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["json-schema-inference", "semantic-type-analysis"]
---
