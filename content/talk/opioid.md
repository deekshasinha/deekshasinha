+++
title = "Preventing Opioid Overdose: From Prediction to Operationalization"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 10

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
#time_start = 2016-11-01T13:00:00
#time_end = 2030-06-01T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
#authors = [ "Jonas Oddur Jonasson", "Neal Kaw", "Deeksha Sinha", "Nikos Trichakis", "Anyi Chen", "Joseph Conte", "Ashley Restaino", "Salvatore Volpe"]


# Abstract and optional shortened version.
#abstract = "The opioid epidemic remains a significant public health challenge in the US. A catalyst for reducing the incidence of opioid-related harm could be the development and operationalization of patient risk stratification models. Prior work has focused on the statistical performance of such models, usually tailored to specific adverse events or sub-populations, without considering operational implications. A particular challenge in this context is predicting the most severe outcomes (fatal overdoses) due to imbalanced datasets. We develop a single population-level model for predicting a full range of adverse opioid-related events. We further explore the capacity requirements of interventions based on our model and address salient implementation trade-offs. We partner with Staten Island Performing Provider System to access claims data and electronic health records for the patient population on Staten Island. We develop a machine learning model for predicting adverse opioid-related outcomes. Subsequently, we conduct a rolling horizon analysis to evaluate the capacity requirements of intervention policies leveraging the model. Finally, we quantify the trade-off in predictive performance against concerns that arise in implementation, such as interpretability, data delay, and prediction horizon length. Our single model risk stratification framework achieves an Area Under the Receiver Operating characteristic Curve (AU-ROC) of 0.95, 0.87, 0.83 for the outcomes of any adverse opioid event, opioid overdose, and fatal opioid overdose, respectively. This model can be used to identify a small intervention cohort (1% of the highest-risk patients) which includes the majority (69%) of adverse opioid events. Our results suggest that predictive performance does not need to be sacrificed to satisfy implementation constraints. Accurate risk stratification models are operationally feasible for implementation, even in the absence of training data on fatal overdoses. The implementation of such models allows for targeted interventions with limited intervention capacity and in the presence of operational constraints."

# Name of event and optional event URL.
event = "INFORMS Healthcare Conference (virtual), 2021; INFORMS Annual Meeting, 2021, Anaheim (USA)"
#POMS 31st Annual Conference, 2021 (virtual; presented by Neal Kaw); Manufacturing and Service Operations Management Conference, 2021 (virtual; presented by Neal Kaw)
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
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

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
