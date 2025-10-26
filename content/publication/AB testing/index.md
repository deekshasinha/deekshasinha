+++
title = "Near Optimal AB Testing"
date = 2013-07-01T00:00:00
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 80 

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors =  ["Nikhil Bhat",  "Vivek F. Farias", "Ciamac C. Moallemi", "Deeksha Sinha"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In Management Science "
#publication_short = "In *WiOpt*"

# Abstract and optional shortened version.
abstract = "We consider the problem of A-B testing when the impact of the treatment is marred by a large number of covariates. Randomization can be highly inecient in such settings, and thus we consider the problem of optimally allocating test subjects to either treatment with a view to maximizing the precision of our estimate of the treatment eect. Our main contribution is a tractable algorithm for this problem in the online setting, where subjects arrive, and must be assigned, sequentially, with covariates drawn from an elliptical distribution with finite second moment. We further characterize the gain in precision aorded by optimized allocations relative to randomized allocations, and show that this gain grows large as the number of covariates grow. Our dynamic optimization framework admits a number of generalizations that incorporate important operational constraints such as the consideration of selection bias, budgets on allocations, and endogenous stopping times. In a set of numerical experiments, we demonstrate that our method simultaneously oers better statistical eciency and less selection bias than state-of-the-art competing biased coin designs."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
links = [
  {type = "pdf", url = "https://pubsonline.informs.org/doi/abs/10.1287/mnsc.2019.3424?journalCode=mnsc"}
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
#[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

