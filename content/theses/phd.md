+++
title = "Optimization for Online Platforms"
date = 2021-01-01T00:00:00
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 10 

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Deeksha Sinha"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
#publication_types = ["0"]

# Publication name and optional abbreviated version.
#publication = "In Companion Proceedings of the Web Conference 2020."
#publication_short = "In (EC'20)"

# Abstract and optional shortened version.
abstract = "In the last decade, there has been a surge in online platforms for providing a wide variety of services. These platforms face an array of challenges that can be mitigated with appropriate modeling and the use of optimization tools. In this thesis, we examine, model, and provide solutions to some of the key challenges. First, we focus on the problem of intelligent SMS routing faced by several online platforms today. In a dynamically changing environment, platforms need to carefully choose SMS ag- gregators to have a high number of text messages being delivered to users at a low cost. To model this problem, we consider a novel variant of the multi-armed bandit (MAB) problem, MAB with cost subsidy, which models many real-life applications where the learning agent has to pay to select an arm and is concerned about optimizing cumulative costs and rewards. We show that naive generalizations of existing MAB algorithms like Upper Confidence Bound and Thompson Sampling do not perform well for the SMS routing problem. For an instance with K arms and time horizon T, we then establish a fundamental lower bound of Ω(K1/3T2/3) on the performance of any online learning algorithm for this problem, highlighting the hardness of our problem in comparison to the classical MAB problem. We also present a simple variant of explore-then-commit and establish near-optimal regret bounds for this algorithm. Lastly, we perform numerical simulations to understand the behavior of a suite of algorithms for various instances and recommend a practical guide to employ different algorithms. Second, we focus on the problem of making real-time personalized recommendations which are now needed in just about every online setting, ranging from media platforms to e-commerce to social networks. While the challenge of estimating user preferences has garnered significant attention, the operational problem of using such preferences to construct personalized offer sets to users is still a challenge, particularly in modern settings with a massive number of items and a millisecond response time requirement. Thus motivated, we propose an algorithm for personalized offer set optimization that runs in time sub-linear in the number of items while enjoying a uniform performance guarantee. Our algorithm works for an extremely general class of problems and models of user choice that includes the mixed multinomial logit model as a special case. Our algorithm can be entirely data-driven and empirical evaluation on a massive content discovery dataset shows that our implementation indeed runs fast and with increased performance relative to existing fast heuristics. Third, we study the problem of modeling purchase of multiple items (in online and offline settings) and utilizing it to display optimized recommendations, which can lead to significantly higher revenues as compared to capturing purchase of only a single product in each transaction. We present a parsimonious multi-purchase family of choice models called the BundleMVL-K family, and develop a binary search based iterative strategy that efficiently computes optimized recommendations for this model. We establish the hardness of computing optimal recommendation sets and characterize structural properties of the optimal solution. The efficacy of our modeling and optimization techniques compared to competing solutions is shown using several real-world datasets on multiple metrics such as model fit, expected revenue gains, and run-time reductions. Fourth, we study the problem of A-B testing for online platforms. Unlike traditional offline A-B testing, online platforms face some unique challenges such as sequential allocation of users into treatment groups, large number of user covariates to balance, and limited number of users available for each experiment, making randomization inefficient. We consider the problem of optimally allocating test subjects to either treatment with a view to maximize the precision of our estimate of the treatment effect. Our main contribution is a tractable algorithm for this problem in the online setting, where subjects must be assigned as they arrive, with covariates drawn from an elliptical distribution with finite second moment. We further characterize the gain in precision afforded by optimized allocations relative to randomized allocations and show that this gain grows large as the number of covariates grows."

# Is this a selected publication? (true/false)
#selected = true

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
  {type = "pdf", url = "/uploads/phd_thesis.pdf"}
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
