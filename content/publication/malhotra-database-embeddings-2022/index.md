---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Investigating Vector Space Embeddings for Database Schema Management"
authors: ["goldy-malhotra"]
date: 2022-01-27T00:00:00-04:00

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-27T00:00:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

abstract: "Text generation in the area of natural language processing as part of the artificial intelligence field has been greatly improving over the last several years. Here we examine the application of vector space word embeddings to provide additional information and context during the text generation process as a way to improve the resultant output through the lens of database normalization. It is known that words encoded into vector space that are closer together in distance generally share meaning or have some semantic or symbolic relationship. This knowledge, paired with the known ability of recurrent neural networks in learning sequences, will be used to examine how vectorizing words can benefit text generation. While the majority of database normalization has been automated, the naming of the generated normalized tables has not. This work seeks to use word embeddings, generated from the data columns of a database table, to give context to a recurrent neural network model while it learns to generate database table names. Using real world data, a recurrent neural network based artificial intelligence model will be paired with a context vector made of word embeddings to observe how effective word embeddings are at providing additional context information during the learning and generation processes. Several methods for generating the context vector will be examined, such as how the word embeddings are generated and how they are combined. The exploration of these methods yielded very promising results in line with the overall goals of the performed work. The benefit of incorporating word embeddings to supply additional information during the text generation process allows for better learning with the goal of generating more human-useful names for newly normalized database tables from their data column titles."

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
