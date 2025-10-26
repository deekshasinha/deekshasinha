+++
title = "The Limits to Learning an SIR Process: Granular Forecasting for Covid-19"
date = 2013-07-01T00:00:00
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 20 

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Jackie Baek", "Vivek F. Farias", "Andreea Georgescu", "Retsef Levi", "Tianyi Peng", "Deeksha Sinha", "Joshua Wilde", "Andrew Zheng"]


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
abstract = "A multitude of forecasting efforts have arisen to support management of the ongoing COVID-19 epidemic. These efforts typically rely on a variant of the SIR process and have illustrated that building effective forecasts for an epidemic in its early stages is challenging. This is perhaps surprising since these models rely on a small number of parameters and typically provide an excellent retrospective fit to the evolution of a disease. So motivated, we provide an analysis of the limits to estimating an SIR process. We show that no unbiased estimator can hope to learn this process until observing enough of the epidemic so that one is approximately two-thirds of the way to reaching the peak for new infections. Our analysis provides insight into a regularization strategy that permits effective learning across simultaneously and asynchronously evolving epidemics. This strategy has been used to produce accurate, granular predictions for the COVID-19 epidemic that has found large-scale practical application in a large US state."

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
  {type = "preprint", url = "https://arxiv.org/pdf/2006.06373.pdf"}
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
