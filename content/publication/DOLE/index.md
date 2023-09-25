---
title: "DOLE: Practical and Bandwidth-Efficient Multiview Video Uploading"
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

abstract: The multiview video service aims at delivering multiple perspectives of a remote scene to users at home. A key support for multiview video services is the transfer of locally captured multiview video to the cloud. However, existing multi-camera systems tend to produce videos of a significant bitrate, making video uploading a serious bottleneck. The root cause is that existing multi-camera systems mostly rely on single-view video codecs like H.264 and H.265 that fail to handle the redundancy across views. To address this problem, there have been proposals for multiview extensions in video coding standards. Still, they are impractical for real-world multi-camera systems due to the inherent demand for a centralized capture device that jointly encodes all views and domain expertise that determines the data flow in multiview video coding. In this paper, we introduce DOLE, a practical and bandwidth-efficient end-to-end multiview video uploading system. DOLE exploits the distributed video coding technique which allows capture devices to work distributedly, requiring no centralized capture device. Additionally, DOLE leverages the learned video codec that adapts the inter-view dependency to a specific scene during streaming, without necessitating domain expertise. Evaluations on diverse multiview scenes show that DOLE outperforms the second best-performing approach with 59%-66% bandwidth savings in peak-signal-to-noise ratio. Additionally, the results of DOLE extends consistently to different quality metrics and hardware configurations.

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
