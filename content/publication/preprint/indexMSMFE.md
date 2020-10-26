---
title: "A multipoint stress-flux mixed finite element method for the Stokes-Biot model"
authors: 
- Sergio Caucao
- admin
- Ivan Yotov
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In this paper we present and analyze a fully-mixed formulation for the coupled problem arising in the interaction between a free fluid and a flow in a poroelastic medium. The flows are governed by the Stokes and Biot equations, respectively, and the transmission conditions are given by mass conservation, balance of stresses and the Beavers-Joseph-Saffman law. We apply dual-mixed formu- lations in both domains, and the symmetry of the Stokes and poroelastic stress tensors are handled by setting the vorticity and structure rotation tensors as auxiliary unknowns. In turn, since the transmission conditions become essential, they are imposed weakly, which yields the introduction of the traces of the fluid velocity, structure velocity, and the poroelastic media pressure on the interface as the associated Lagrange multipliers. The existence and uniqueness of a solution are established for continuous and semidiscrete continuous-in-time formulations in both matching and non-matching grids, together with the corresponding stability bounds. In addition, we develop a new multipoint stress-flux mixed finite element method by involving the vertex quadrature rule, which allows for local elimination of the stresses, rotations and Darcy fluxes. Well-posedness and error analysis with corresponding rates of convergences are complemented by several numerical experiments.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: '#'
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
# ---

# {{% alert note %}}
# Click the *Slides* button above to demo Academic's Markdown slides feature.
# {{% /alert %}}

# Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
