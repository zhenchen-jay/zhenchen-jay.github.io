---
title: "Fine Wrinkling on Coarsely Meshed Thin Shells"
authors:
- Zhen Chen
- Hsiao-yu Chen
- Danny M. Kaufman
- Mélina Skouras
- Etienne Vouga

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-08-08"
doi: "10.1145/3462758"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Graphics (Presentation in SIGGRAPH 2022)"
publication_short: "ACM Trans. on Graphics"

abstract: We propose a new model and algorithm to capture the high-definition statics of thin shells via coarse meshes. This model predicts global, fine-scale wrinkling at frequencies much higher than the resolution of the coarse mesh; moreover, it is grounded in the geometric analysis of elasticity, and does not require manual guidance, a corpus of training examples, nor tuning of ad-hoc parameters. We first approximate the coarse shape of the shell using tension field theory, in which material forces do not resist compression. We then augment this base mesh with wrinkles, parameterized by an amplitude and phase field that we solve for over the base mesh, which together characterize the geometry of the wrinkles. We validate our approach against both physical experiments and numerical simulations, and show that our algorithm produces wrinkles qualitatively similar to those predicted by traditional shell solvers requiring orders of magnitude more degrees of freedom.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: /uploads/TFW.pdf
url_code: 'https://github.com/zhenchen-jay/WrinkledTensionFields.git'
url_dataset: 'https://www.dropbox.com/home/WTF_dataset'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=8kWz7wFIQlA'
links:
  - name: "Results"
    url: 'https://www.youtube.com/watch?v=-D1GRrBvYOY'
  - name: "ACM Trans. on Graphics 2021"
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
