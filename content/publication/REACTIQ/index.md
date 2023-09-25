---
title: "REACTIQ: Resilient, Efficient and Accurate Query Serving via Conjugate Computation"
authors:
- Bo Chen
date: "2023-09-21T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In a query-serving system, delivering a response to the user within the specified Service Level Objectives (SLO) is crucial. However, machine learning (ML)-based query services, typically deployed in data centers, are susceptible to failures, which can lead to SLO violations. Avoiding these failures is essential. Although issuing redundant queries to additional servers is a straightforward solution, our preliminary study reveals a significant amount of computation being carried out on replica without contributing to the query outcome, a phenomenon termed as futile replica. This paper describes the design and implementation of REACTIQ, a resilient, efficient, and accurate query-serving system that overcomes futile replicas via a novel computation paradigm, conjugation computation. It allows distributed model instances to leverage the computations performed by others to complete their own inferences, striking a better balance of accuracy and computation. REACTIQ comprises two key components: i) model sharding that replaces the canonical ML inference pipeline with a collaborative neural network inference framework co-design, and ii) model conjugation that facilitates accurate query serving via enhanced model training techniques. Evaluation results show that, in comparison to a non-replication-based baseline with similar computational resources, REACTIQ achieved significant reductions in query latencies, ranging from 13% to 62.8%, across various percentiles while maintaining near-optimal accuracy. Furthermore, REACTIQ demonstrated substantial improvements in top-1 accuracy compared to replication-based approaches, with enhancements of up to 2.9% while maintaining comparable computational resources and query latencies."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
