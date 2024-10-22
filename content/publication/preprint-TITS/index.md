---
title: "Towards Efficient Point Cloud Classification  via Critical Point Aware Pooling with Adaptive Learnable Threshold"
authors:
- Tong Sang
- admin
- Xiaofeng Zou
- Zeng Zeng
- Xulei Yang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2022-08-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: LWith the rapid development of our transportation systems that has brought a great deal of convenience in our daily life, automatic driving has been becoming popular. Point clouds offer unparalleled advantages as 3D data in sensing the surrounding environment. However, a Down-Sampling method for point clouds is urgently demanded because point cloud datasets are usually huge and impose a great computational burden on edge computing platforms, such as automobiles. In this work we propose a Critical Point Aware Pooling (CPAPool) method with learnable thresholds. It adaptively learns the importance of nodes in point cloud data and scores them, followed by pooling the point cloud data according to learnable thresholds. This method uses only the important points in the point cloud to participate in the calculation process while  effectively improving the classification performance of the existing architectures, which can be easily embedded with CPAPool. We have conducted experiments on the ModelNet10 and ModelNet40 datasets and demonstrated  that our proposed method effectively reduces the number of computation points involved, resulting in better accuracy and significant improvement in inference speed.

# Summary. An optional shortened abstract.
summary: Critical point aware pooling, Graph neural networks,  Point clouds, Learnable importance.

tags:
- Source Themes
featured: false

# links:
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

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
