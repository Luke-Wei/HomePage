---
title: 'Latent Vector Prototypes Guided Conditional Face Synthesis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xulei Yang$
  - Tong Sang$
  - Huijiao Wang
  - Zou Xiaofeng
  - Cheng Zhongyao
  - Zhao Ziyuan
  - Zeng Zeng

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In The 29th IEEE International Conference on Image Processing
publication_short: In ICIP

abstract: LRecent advances in deep neural networks, especially in generative adversarial networks (GAN), have shown remarkable progress in face image generations. However, most of the existing face image generators can only synthesize random face images, but are not able to control the attributes of the generated face images. Though conditional GAN based methods can manipulate the attributes to some extent, but can only generate low-resolution face images up to $256\times 256$. In this study, based on StyleGAN, one of the state-of-the-art image generators for synthesizing high-quality face images, we propose a simple but efficient approach to generate high-resolution and hyper-realistic face images with any desired attribute. By training an attribute classifier to assign attribute labels to given synthesized face images, we build the links between latent vectors and face attributes. In such a way, the latent vectors can be grouped into different clusters, one cluster corresponding to one face attribute, respectively. We then extract the prototypes for the clusters, which are used to control the attribute of the generated face image. Extensive experiments demonstrate the effectiveness of the proposed approach for high-quality face image generation with predefined attributes. 

# Summary. An optional shortened abstract.
summary: Conditional Face Generation,  Generative Adversarial Networks, Prototype Clustering

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
