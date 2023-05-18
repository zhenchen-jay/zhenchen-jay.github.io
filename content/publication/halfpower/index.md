---
title: "Half-Space Power Diagrams and Discrete Surface Offsets"
date: 2019-10-14
authors:
- Zhen Chen
- Daniele Panozzo
- Jérémie Dumas

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-10-14"
doi: "10.1109/TVCG.2019.2945961"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Visualization and Computer Graphics 2019 (Presentation in SGP 2020)"
publication_short: "IEEE TVCG"

abstract: We present an efficient, trivially parallelizable algorithm to compute offset surfaces of shapes discretized using a dexel data structure. Our algorithm is based on a two-stage sweeping procedure that is simple to implement and efficient, entirely avoiding volumetric distance field computations typical of existing methods. Our construction is based on properties of half-space power diagrams, where each seed is only visible by a half-space, which were never used before for the computation of surface offsets. The primary application of our method is interactive modeling for digital fabrication. Our technique enables a user to interactively process high-resolution models. It is also useful in a plethora of other geometry processing tasks requiring fast, approximate offsets, such as topology optimization, collision detection, and skeleton extraction. We present experimental timings, comparisons with previous approaches, and provide a reference implementation in the supplemental material.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1109/TVCG.2019.2945961'
url_code: 'https://github.com/geometryprocessing/voroffset'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=u8qtOkJqEO0'
links:
  - name: "Preprint"
    url: "https://cims.nyu.edu/gcl/papers/2019-VorOffset.pdf"

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
