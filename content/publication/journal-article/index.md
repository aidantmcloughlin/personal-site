---
title: "Shared Differential Expression-Based Distance Reflects Global Cell Type Relationships in Single-Cell RNA Sequencing Data"
authors:
- admin
- Haiyan Huang
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-08-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: #"2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Computational Biology, Vol. 29*(8)"
publication_short: ""

abstract: Unsupervised cell clustering on the basis of meaningful biological variation in single-cell RNA sequencing (scRNA seq) data has received significant attention, as it assists with ontological subpopulation identification among the data. A key step in the clustering process is to compute distances between the cells under a specified distance measure. Although particular distance measures may successfully separate cells into biologically relevant clusters, they may fail to retain global structure of the data, such as relative similarity between the cell clusters. In this article, we modify a biologically motivated distance measure, SIDEseq, for use of aggregate comparisons of cell types in large single-cell assays, and demonstrate that, across simulated and real scRNA seq data, the distance matrix more consistently retains global cell type relationships than commonly used distance measures for scRNA seq clustering. We call the modified distance measure “SIDEREF.” We explore spectral dimension reduction of the SIDEREF distance matrix as a means of noise filtering, similar to principal components analysis applied directly to expression data. We utilize a summary measure of relative cell type distances to better display the cell group relationships. SIDEREF visualizations more consistently reflect global structures in the data than other commonly considered distance measures. We utilize relative cell type distances and the SIDEREF distance measure to uncover compositional differences between annotated leukocyte cell groups in a compendium of Mus musculus scRNA seq assays comprising 12 tissues. SIDEREF and associated analysis is openly available on GitHub.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex #sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.liebertpub.com/doi/10.1089/cmb.2021.0652
url_code: 'https://github.com/aidantmcloughlin/SIDEREF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Cell group relative distances under various distance measures.'
  focal_point: ""
  preview_only: true

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
