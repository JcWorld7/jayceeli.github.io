---
title: "Fine-Tuning Generative Models for Text Summarization with Limited Data (in progress)"
authors:
- admin
- Zhu Li
- Ariel Aloe
- Kishlay Jha
date: "2025-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article"]
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The rapid increase in scientific publications across disciplines has made it harder for researchers to stay up-to-date with the latest literature. They often spend hours skimming through papers just to find key information or determine whether a study is relevant to their needs. This study introduces a practical method for fine-tuning pretrained generative language models to automatically generate structured summaries from scientific articles. This helps researchers not only find relevant content more quickly but also understand study details more effectively. Using the PICO (Population, Intervention, Comparison, Outcome) framework and including elements like Sample Size, Design Description, and Statistical Analysis as a case example, we examine how such a model can be fine-tuned on limited, manually annotated data using lightweight methods, such as prompt engineering, hyperparameter tuning, and generative adapters.

# Summary. An optional shortened abstract.
summary: This study introduces a practical method for fine-tuning pretrained generative language models to automatically generate structured summaries from scientific articles.

tags:
- Large Language Models

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
