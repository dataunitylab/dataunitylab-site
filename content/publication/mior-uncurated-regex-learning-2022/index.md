---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning from Uncurated Regular Expressions"
authors: ["admin"]
date: 2022-07-14T00:00:00-04:00

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-14T00:00:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Computing Research Repository"

abstract: "Significant work has been done on learning regular expressions from a set of data values. Depending on the domain, this approach can be very successful. However, significant time is required to learn these expressions and the resulting expressions can either become very complex or inaccurate in the presence of dirty data. The alternative of manually writing regular expressions becomes unattractive when faced with a large number of values which must be matched.

As an alternative, we propose learning from a large corpus of manually authored, but uncurated regular expressions mined from a public repository. The advantage of this approach is that we are able to extract salient features from a set of strings with limited overhead to feature engineering. Since the set of regular expressions covers a wide range of application domains, we expect them to widely applicable.

To demonstrate the potential effectiveness of our approach, we train a model using the extracted corpus of regular expressions for the class of semantic type classification. While our approach generally yields results that are inferior to the state of the art, our training data is much smaller and simpler and a closer analysis of the performance results suggests this approach holds significant promise. We also demonstrate the possibility of using uncurated regular expressions for unsupervised learning. "

summary: "Semantic type classification using a large regular expression corpus."

tags: []
categories: []
featured: true

url_pdf: https://arxiv.org/pdf/2206.06747.pdf

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
