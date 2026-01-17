---
title: 'The Effect of Different Text Processing Techniques on Text Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Robert Ford

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: |
  Systematic reviews constitute a foundational method in evidence synthesis, but are constrained by the time-intensive process of screening large volumes of studies. Natural language processing (NLP) and machine learning offer promising approaches for automating text classification in this context, yet the impact of preprocessing choices on model performance remains underexplored. This study investigates how combinations of three fundamental text preprocessing techniques—Tokenization, Stopword removal, and Stemming affect the performance of a text classification model. Using 602 studies (titles and abstracts) drawn from a scoping review of school-based mental health interventions, we implemented a 4 × 4 × 4 factorial design including 64 unique preprocessing conditions. Model performance was evaluated on training and testing sets across seven metrics: Accuracy, Sensitivity, Specificity, Kappa, Positive Predictive Value, Negative Predictive Value, and Balanced Accuracy. Results indicate that preprocessing choices significantly influence classification outcomes, with tokenization strategies (particularly unigram-bigram-trigram and bigram-trigram combinations) exerting the strongest effect on performance variability. While stopword removal and stemming yielded more stable results, tokenization configurations were achieving the highest metric values. Importantly, the effects of preprocessing observed in the training set did not fully generalize to the testing set, highlighting the need to balance performance and generalization when designing preprocessing pipelines. Correlation analyses across conditions revealed consistent relationships among evaluation metrics, highlighting the need for multidimensional assessment in imbalanced data contexts. This study underscores the importance of carefully selecting and reporting preprocessing strategies in NLP-based systematic review automation and provides openly available datasets and annotated R scripts to promote reproducibility. Findings contribute to refining evidence synthesis workflows and advancing methodological transparency in text classification research.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
