+++
title = "Optimizing Revenue Over Data Driven Assortments"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
#time_start = 2016-11-06T13:00:00
#time_end = 2030-06-01T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
#authors = [ "Theja Tulabandhula", "Deeksha Sinha", "Saketh Karra"]

# Abstract and optional shortened version.
#abstract = "We revisit the problem of large-scale assortment optimization under the multinomial logit choice model without any assumptions on the structure of the feasible assortments. Scalable real-time assortment optimization has become essential in e-commerce operations due to the need for personalization and the availability of a large variety of items. While this can be done when there are simplistic assortment choices to be made, not imposing any constraints on the collection of feasible assortments gives more flexibility to incorporate insights of store-managers and historically well-performing assortments. We design fast and flexible algorithms based on variations of binary search that find the revenue of the (approximately) optimal assortment. We speed up the comparisons steps using novel vector space embeddings, based on advances in the information retrieval literature. For an arbitrary collection of assortments, our algorithms can find a solution in time that is sub-linear in the number of assortments and for the simpler case of cardinality constraints - linear in the number of items (existing methods are quadratic or worse). Empirical validations using the Billion Prices dataset and several retail transaction datasets show that our algorithms are competitive even when the number of items is ∼ 105 (100x larger instances than previously studied). "

# Name of event and optional event URL.
event = "INFORMS Annual Meeting, 2016, Nashville (USA); 6th ISB-POMS Workshop, 2018, Hyderabad (India)"
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
