+++
title = "Multi-armed Bandits with Cost Subsidy"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = true

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 20

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
#time_start = 2016-11-01T13:00:00
#time_end = 2030-06-01T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
#authors = ["Deeksha Sinha", "Karthik Abinav Sankararama", "Abbas Kazerouni", "Vashist Avadhanula"]

# Abstract and optional shortened version.
#abstract = "In this paper, we consider a novel variant of the multi-armed bandit (MAB) problem, MAB with cost subsidy, which models many real-life applications where the learning agent has to pay to select an arm and is concerned about optimizing cumulative costs and rewards. We present two applications, intelligent SMS routing problem and ad audience optimization problem faced by several businesses (especially online platforms), and show how our problem uniquely captures key features of these applications. We show that naive generalizations of existing MAB algorithms like Upper Confidence Bound and Thompson Sampling do not perform well for this problem. We then establish a fundamental lower bound on the performance of any online learning algorithm for this problem, highlighting the hardness of our problem in comparison to the classical MAB problem. We also present a simple variant of explore-then-commit and establish near-optimal regret bounds for this algorithm. Lastly, we perform extensive numerical simulations to understand the behavior of a suite of algorithms for various instances and recommend a practical guide to employ different algorithms."

# Name of event and optional event URL.
event = "Trans-Atlantic Doctoral Conference (virtual), 2021; Manufacturing and Service Operations Management Conference (virtual), 2021; Artificial Intelligence and Statistics (virtual), 2021, Conference on Artificial Intelligence, Machine Learning, and Business Analytics (virtual; presented by Vashist Avadhanula), 2020"

#event_url = "https://example.org"


# Location of event.
#location = "London, United Kingdom"

# Is this a selected talk? (true/false)
#selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "data_driven_ast_opt"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

> [!NOTE]
> Click on the **Slides** button above to view the built-in slides feature.

Slides can be added in a few ways:

- **Create** slides using Academic's *Slides* feature and link using `url_slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
