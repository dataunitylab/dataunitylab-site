---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Comprehending Semantic Types in JSON Data with Graph Neural Networks"
authors: ["shuang-wei", "admin"]
date: 2023-07-24T10:23:48-04:00

# Schedule page publish date (NOT publication's date).
publishDate: 2023-07-24T10:23:48-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

abstract: "Semantic types are a more powerful and detailed way of describing data than atomic types such as strings or integers. They establish connections between columns and concepts from the real world, providing more nuanced and fine-grained information that can be useful for tasks such as automated data cleaning, schema matching, and data discovery. Existing deep learning models trained on large text corpora have been successful at performing single-column semantic type prediction for relational data. However, in this work, we propose an extension of the semantic type prediction problem to JSON data, labeling the types based on JSON Paths. Similar to columns in relational data, JSON Path is a query language that enables the navigation of complex JSON data structures by specifying the location and content of the elements. We use a graph neural network to comprehend the structural information within collections of JSON documents. Our model outperforms a state-of-the-art existing model in several cases. These results demonstrate the ability of our model to understand complex JSON data and its potential usage for JSON-related data processing tasks."

# Summary. An optional shortened abstract.
summary: "Graph neural networks for semantic type detection in JSON."

url_pdf: uploads/publications/Wei2023.pdf

tags: []
categories: []
featured: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["semantic-type-analysis"]
---
