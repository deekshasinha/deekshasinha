+++
title = "Preventing Opioid Overdose: From Prediction to Operationalization"
date = 2013-07-01T00:00:00
draft = false

#weight specifies the order in which the publications will be displayed - smaller weight means more important
weight = 10

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Jonas Oddur Jonasson", "Neal Kaw", "Deeksha Sinha", "Nikos Trichakis", "Anyi Chen", "Joseph Conte", "Ashley Restaino", "Salvatore Volpe"]


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
#publication = "In 21st ACM Conference on Economics & Computation (EC’20)."
#publication_short = "In (EC'20)"

# Abstract and optional shortened version.
abstract = "The opioid epidemic remains a significant public health challenge in the US. A catalyst for reducing the incidence of opioid-related harm could be the development and operationalization of patient risk stratification models. Prior work has focused on the statistical performance of such models, usually tailored to specific adverse events or sub-populations, without considering operational implications. A particular challenge in this context is predicting the most severe outcomes (fatal overdoses) due to imbalanced datasets. We develop a single population-level model for predicting a full range of adverse opioid-related events. We further explore the capacity requirements of interventions based on our model and address salient implementation trade-offs. We partner with Staten Island Performing Provider System to access claims data and electronic health records for the patient population on Staten Island. We develop a machine learning model for predicting adverse opioid-related outcomes. Subsequently, we conduct a rolling horizon analysis to evaluate the capacity requirements of intervention policies leveraging the model. Finally, we quantify the trade-off in predictive performance against concerns that arise in implementation, such as interpretability, data delay, and prediction horizon length. Our single model risk stratification framework achieves an Area Under the Receiver Operating characteristic Curve (AU-ROC) of 0.95, 0.87, 0.83 for the outcomes of any adverse opioid event, opioid overdose, and fatal opioid overdose, respectively. This model can be used to identify a small intervention cohort (1% of the highest-risk patients) which includes the majority (69%) of adverse opioid events. Our results suggest that predictive performance does not need to be sacrificed to satisfy implementation constraints. Accurate risk stratification models are operationally feasible for implementation, even in the absence of training data on fatal overdoses. The implementation of such models allows for targeted interventions with limited intervention capacity and in the presence of operational constraints."

# Is this a selected publication? (true/false)
selected = false

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
