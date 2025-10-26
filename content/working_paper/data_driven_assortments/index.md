+++
title = "Optimizing Revenue while showing Relevant Assortments at Scale"
date = 2013-07-01T00:00:00
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 50 

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Theja Tulabandhula", "Deeksha Sinha"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
#publication = "In Companion Proceedings of the Web Conference 2020."
#publication_short = "In (EC'20)"

# Abstract and optional shortened version.
abstract = "Scalable real-time assortment optimization has become essential in e-commerce operations due to the need for personalization and the availability of a large variety of items. While this can be done when there are simplistic assortment choices to be made, imposing constraints on the collection of feasible assortments gives more flexibility to incorporate insights of store-managers and historically well-performing assortments. We design fast and flexible algorithms based on variations of binary search that find the revenue of the (approximately) optimal assortment. In particular, we revisit the problem of large-scale assortment optimization under the multinomial logit choice model without any assumptions on the structure of the feasible assortments. We speed up the comparisons steps using novel vector space embeddings, based on advances in the fields of information retrieval and machine learning. For an arbitrary collection of assortments, our algorithms can find a solution in time that is sub-linear in the number of assortments and for the simpler case of cardinality constraints - linear in the number of items (existing methods are quadratic or worse). Empirical validations using the Billion Prices dataset and several retail transaction datasets show that our algorithms are competitive even when the number of items is ∼105 (100x larger instances than previously studied)."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
#tags = []

# Links (optional).
links = [
  {type = "preprint", url = "https://arxiv.org/abs/2003.04736"}
]

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
