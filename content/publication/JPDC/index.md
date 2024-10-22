---
title: "A job scheduling algorithm based on parallel workload prediction on computational grid"
authors:
- Xiaoyong Tang
- Yi Liu
- Tan Deng
- Zexin Zeng
- Haowei Huang
- admin
- Xiaorong Li
- Li Yang

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Parallel and Distributed Computing
publication_short: "JPDC"

abstract: Generally, the computational grid consists of a large number of computing nodes, some of them are idle due to the uneven geographical distribution of computing requirements. This may cause workload unbalancing problems, which affect the performance of large-scale computational grids. In order to balance the computing requirements and computing nodes, we propose a job scheduling algorithm based on the workload prediction of computing nodes. We first analyze the causes of workload imbalance and the feasibility of reallocating computing resources. Secondly, we design an application and workload-aware scheduling algorithm (AWAS) by combining the previously designed workload prediction model. To reduce the complexity of the AWAS algorithm, we propose a parallel job scheduling method based on computing node workload prediction. The experiments show that the AWAS algorithm can balance the workload among different computing nodes on the real-world dataset. In addition, we propose the parallelism of workload prediction model from the perspective of internal structure and data set to make AWAS apply to more computing nodes of the large-scale computing grids. Experimental results show that the combination of the two can achieve satisfactory acceleration efficiency.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects: []

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
