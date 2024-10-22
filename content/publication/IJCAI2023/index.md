---
title: 'Bayesian optimization with switching cost: Regret analysis and lookahead variants'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Peng Liu
  - Haowei Wang
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 32nd International Joint Conference on Artificial Intelligence
publication_short: In IJCAI

abstract: Bayesian Optimization (BO) has recently received increasing attention due to its efficiency in optimizing expensive-to-evaluate functions. For some practical problems, it is essential to consider the path-dependent switching cost between consecutive sampling locations given a total traveling budget. For example, when using a drone to locate cracks in a building wall or search for lost survivors in the wild, the search path needs to be efficiently planned given the limited battery power of the drone. Tackling such problems requires a careful cost-benefit analysis of candidate locations and balancing exploration and exploitation. In this work, we formulate such a problem as a constrained Markov Decision Process (MDP) and solve it by proposing a new distance-adjusted multi-step look-ahead acquisition function, the distUCB, and using rollout approximation. We also provide a theoretical regret analysis of the distUCB-based Bayesian optimization algorithm. In addition, the empirical performance of the proposed algorithm is tested based on both synthetic and real data experiments, and it shows that our cost-aware non-myopic algorithm performs better than other popular alternatives.



# Summary. An optional shortened abstract.
summary: Machine Learning, Bayesian learning, Hyperparameter optimization

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

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder.
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
