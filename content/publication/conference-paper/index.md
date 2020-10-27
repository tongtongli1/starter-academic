---
title: "A cell-centered finite volume method for the Navier-Stokes/Biot model"
authors:
- Sergio Caucao
- admin
- Ivan Yotov
date: "2020-06-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Finite Volumes for Complex Applications IX*
publication_short: In *FVCA 2020*

abstract: We develop a cell-centered finite volume method for the Navier–Stokes/Biot model, based on a fully mixed formulation with weakly symmetric stresses. The multipoint stress mixed finite element method is employed for the Navier–Stokes and elasticity equations, while the multipoint flux mixed finite element method is used for Darcy’s flow. These methods allow for local elimination of the fluid and poroelastic stresses, vorticity, and rotation, resulting in a positive definite finite volume scheme for the fluid and structure velocities and the Darcy pressure, coupled via Lagrange multipliers on the interface to impose the transmission conditions.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-43651-3_29
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

