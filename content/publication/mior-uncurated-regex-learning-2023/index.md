---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning from Uncurated Regular Expressions"
authors: ["admin"]
date: 2023-06-23:00:00:00-04:00
doi: "10.1145/3596225.3596226"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-23:00:00:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 1st 1st Workshop on Simplicity in Management of Data"
publication_short: "SiMoD '23"

abstract: "Significant work has been done on learning regular expressions from a set of data values. Depending on the domain, this approach can be very successful. However, significant time is required to learn these expressions and the resulting expressions can become either very complex or inaccurate in the presence of dirty data. The alternative of manually writing regular expressions becomes unattractive when faced with a large number of values that must be matched.

As an alternative, we propose learning from a large corpus of manually authored, but uncurated regular expressions mined from a public repository. The advantage of this approach is that we are able to extract salient features from a set of strings with limited overhead to feature engineering. Since the set of regular expressions covers a wide range of application domains, we expect them to be widely applicable.

To demonstrate the potential effectiveness of our approach, we train a model using the extracted corpus of regular expressions for the class of semantic type classification. While our approach yields results that are overall inferior to the state-of-the-art, our feature extraction code is an order of magnitude smaller, and our model outperforms a popular existing approach on some classes. We also demonstrate the possibility of using uncurated regular expressions for unsupervised learning."

summary: "Semantic type classification using a large regular expression corpus."

tags: []
categories: []
featured: true

url_code: "https://github.com/dataunitylab/semantic-regex.git"
url_pdf: "https://arxiv.org/pdf/2206.06747.pdf"
url_slides: "https://speakerdeck.com/michaelmior/learning-from-uncurated-regular-expressions-for-semantic-type-classification-simod-2023"

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
