---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Aurélien Alfonsi

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "IMA Journal of Numerical Analysis"
publication_short: "IMAJNA"

abstract: We present new high order approximations schemes for the Cox–Ingersoll–Ross (CIR) process that are obtained by using a recent technique developed by Alfonsi and Bally (2021, A generic construction for high order approximation schemes of semigroups using random grids. Numer. Math., 148, 743–793) for the approximation of semigroups. The idea consists in using a suitable combination of discretization schemes calculated on different random grids to increase the order of convergence. This technique coupled with the second order scheme proposed by Alfonsi (2010, High order discretization schemes for the CIR process: application to affine term structure and Heston models. Math. Comp., 79, 209–237) for the CIR leads to weak approximations of all orders. Despite the singularity of the square-root volatility coefficient, we show rigorously this order of convergence under some restrictions on the volatility parameters. We illustrate numerically the convergence of these approximations for the CIR process and for the Heston stochastic volatility model and show the computational time gain they give.

# Summary. An optional shortened abstract.
summary: Developed high order approximations schemes for the Cox–Ingersoll–Ross (CIR) process, proved theorem of rate of convergence.

tags:
- Source Themes
featured: false

hugoblox:
  ids:
    arxiv: 2209.13334

links:
  - type: pdf
    url: [https://epubs.siam.org/journal/sjfmbj](https://academic.oup.com/imajna/article-abstract/44/4/2277/7246577)
  - type: code
    url: ""
  - type: project
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
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
slides: ""


# > [!NOTE]
# > Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

# > [!NOTE]
# > Create your slides in Markdown - click the *Slides* button to check out the example.

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

---
