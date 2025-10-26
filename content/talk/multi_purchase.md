+++
title = "Multi-Purchase Behavior: Modeling and Optimization"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false


#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 30


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
#time_start = 2016-11-01T13:00:00
#time_end = 2030-06-01T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
#authors = ["Deeksha Sinha", "Theja Tulabandhula", "Prasoon Patidar"]

# Abstract and optional shortened version.
#abstract = "We study the problem of modeling purchase of multiple items and utilizing it to display optimized recommendations, which is a central problem for online e-commerce platforms. Rich personalized modeling of users and fast computation of optimal products to display given these models can lead to significantly higher revenues and simultaneously enhance the end user experience. We present a parsimonious multi-purchase family of choice models called the BundleMVL-K family, and develop a binary search based iterative strategy that efficiently computes optimized recommendations for this model. This is one of the first attempts at operationalizing multi-purchase class of choice models. We characterize structural properties of the optimal solution, which allow one to decide if a product is part of the optimal assortment in constant time, reducing the size of the instance that needs to be solved computationally. We also establish the hardness of computing optimal recommendation sets. We show one of the first quantitative links between modeling multiple purchase behavior and revenue gains. The efficacy of our modeling and optimization techniques compared to competing solutions is shown using several real world datasets on multiple metrics such as model fitness, expected revenue gains and run-time reductions. The benefit of taking multiple purchases into account is observed to be 6−8% in relative terms for the Ta Feng and UCI shopping datasets when compared to the MNL model for instances with ∼1500 products. Additionally, across 8 real world datasets, the test log-likelihood fits of our models are on average 17% better in relative terms. The simplicity of our models and the iterative nature of our optimization technique allows practitioners meet stringent computational constraints while increasing their revenues in practical recommendation applications at scale."

# Name of event and optional event URL.
event = "Manufacturing and Service Operations Management Conference 2021 (Special Interest Group), 2020 (virtual); INFORMS DMDA Workshop, 2020 (virtual); ORC Student Seminar, Fall 2020 (virtual); NeurIPS Workshop on Sets & Partitions, 2019 (poster)"
#The Web Conference, 2020 (virtual; presented by Prasoon Patidar);
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
