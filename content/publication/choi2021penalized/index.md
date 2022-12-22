---
title: "Penalized I-spline Monotone Regression Estimation"
authors:
- admin
- JungJun Lee
- Jae-Hwan Jhong
- Ja-Yong Koo
date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Communications in Statistics - Simulation and Computation*"
publication_short: ""

abstract: We propose a penalized regression spline estimator for monotone regression. To construct the estimator, we adopt the I-splines with the total variation penalty. The I-splines lend themselves to the monotonicity because of the simpler form of restrictions, and the total variation penalty induces a data-driven knot selection scheme. A coordinate descent algorithm is developed for the estimator. If the number of complexity parameter candidates sufficiently increases, the algorithm considers all possible monotone linear spline fits to the given data. The pruning process of the algorithm not only provides numerical stability, but also implements the data-driven knot selection. We also compute the maximum candidate of the complexity parameter to facilitate complexity parameter selection. Extensive numerical studies show that the proposed estimator captures spatially inhomogeneous behaviors of data, such as sudden jumps.

tags:
- Coordinate descent algorithm
- I-splines
- Knot selection
- Maximum complexity parameter
- Monotone regression
- Total variation penalty
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.tandfonline.com/doi/abs/10.1080/03610918.2019.1630433'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
---
