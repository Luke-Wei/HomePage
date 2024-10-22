---
title: 'Wafer Map Defect Patterns Semi-Supervised Classification Using Latent Vector Representation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wei Zhao
  - Xiaoyan Zheng
  - Zeng Zeng
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-04-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In the 10th IEEE International Conference on Cybernetics and Intelligent Systems (CIS) and the 10th IEEE International Conference on Robotics, Automation and Mechatronics (RAM)
publication_short: In CIS-RAM

abstract: As the globalization of semiconductor design and manufacturing processes continues, the demand for defect detection during integrated circuit fabrication stages is becoming increasingly critical, playing a significant role in enhancing the yield of semiconductor products. Traditional wafer map defect pattern detection methods involve manual inspection using electron microscopes to collect sample images, which are then assessed by experts for defects. This approach is labor-intensive and inefficient. Consequently, there is a pressing need to develop a model capable of automatically detecting defects as an alternative to manual operations. In this paper, we propose a method that initially employs a pre-trained VAE model to obtain the fault distribution information of the wafer map. This information serves as guidance, combined with the original image set for semi-supervised model training. During the semi-supervised training, we utilize a teacher-student network for iterative learning. The model presented in this paper is validated on the benchmark dataset WM-811K wafer dataset. The experimental results demonstrate superior classification accuracy and detection performance compared to state-of-the-art models, fulfilling the requirements for industrial applications. Compared to the original architecture, we have achieved significant performance improvement.

# Summary. An optional shortened abstract.
summary: Defect detection; semi-supervised learning; unsupervised learning; variation autoencoder

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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
