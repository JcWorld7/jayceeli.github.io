---
title: Presentation

event: IRT
event_url: https://example.org

location: UIowa
address:
  street: 240 S Madison St
  city: Iowa City
  region: IA
  postcode: '52242'
  country: United States

summary: Integrating Item Response Theory with Large Language Models to Improve the Measurement Quality of Automated Text-Based Assessments.
abstract: 'Large language models (LLMs) are increasingly used for text classification tasks in educational and psychological research; however, their evaluation is typically limited to aggregate performance metrics that provide little insight into measurement quality at the item level. This study investigates whether Item Response Theory (IRT) can be used to evaluate and calibrate the measurement properties of LLM-based text classification systems. In this framework, individual text instances are treated as items, and LLM classification outcomes are modeled as item responses, allowing estimation of item difficulty and discrimination parameters. Using multiple LLM configurations and benchmark text datasets, we fit dichotomous and ordinal IRT models to examine variability in classification performance attributable to both model ability and item characteristics. Results demonstrate that IRT provides meaningful differentiation among text instances, identifying systematically difficult items and texts that are most informative for distinguishing higher- and lower-performing models. Furthermore, IRT-based calibration improves the interpretability and comparability of LLM performance across datasets and model variants. Findings suggest that IRT offers a principled measurement framework for evaluating LLM-based classification systems, extending beyond accuracy-based evaluation toward validity, fairness, and interpretability in automated text analysis.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-06-01T13:00:00Z'
date_end: '2025-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com'
url_pdf: ''
url_slides: 'https://slideshare.net'
url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
