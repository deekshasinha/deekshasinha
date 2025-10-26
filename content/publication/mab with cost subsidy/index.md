+++
title = "Multi-armed Bandits with Cost Subsidy"
date = 2013-07-01T00:00:00
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 60 

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Deeksha Sinha", "Karthik Abinav Sankararama", "Abbas Kazerouni", "Vashist Avadhanula"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "International Conference on Artificial Intelligence and Statistics, 2021."
publication_short = "In (AISTATS'21)"

# Abstract and optional shortened version.
abstract = "In this paper, we consider a novel variant of the multi-armed bandit (MAB) problem, MAB with cost subsidy, which models many real-life applications where the learning agent has to pay to select an arm and is concerned about optimizing cumulative costs and rewards. We present two applications, intelligent SMS routing problem and ad audience optimization problem faced by a number of businesses (especially online platforms) and show how our problem uniquely captures key features of these applications. We show that naive generalizations of existing MAB algorithms like Upper Confidence Bound and Thompson Sampling do not perform well for this problem. We then establish fundamental lower bound of Ω(K1/3T2/3) on the performance of any online learning algorithm for this problem, highlighting the hardness of our problem in comparison to the classical MAB problem (where T is the time horizon and K is the number of arms). We also present a simple variant of explore-then-commit and establish near-optimal regret bounds for this algorithm. Lastly, we perform extensive numerical simulations to understand the behavior of a suite of algorithms for various instances and recommend a practical guide to employ different algorithms."

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
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_preprint = "/files/reco_sub_linear_website.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

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
