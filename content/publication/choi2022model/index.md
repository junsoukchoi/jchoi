---
title: "Model-Based Causal Discovery for Zero-Inflated Count Data"
authors:
- admin
- Yang Ni
date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Machine Learning Research*, just accepted"
publication_short: ""

abstract: Zero-inflated count data arise in a wide range of scientific areas such as social science, biology, and genomics. Very few causal discovery approaches can adequately account for excessive zeros as well as various features of multivariate count data such as overdispersion. In this paper, we propose a new zero-inflated generalized hypergeometric directed acyclic graph (ZiG-DAG) model for inference of causal structure from purely observational zero-inflated count data. The proposed ZiG-DAGs exploit a broad family of generalized hypergeometric probability distributions and are useful for modeling various types of zero-inflated count data with great flexibility. In addition, ZiG-DAGs allow for both linear and nonlinear causal relationships. We prove that the causal structure is identifiable for the proposed ZiG-DAGs via a general proof technique for count data, which is applicable beyond the proposed model for investigating causal identifiability. Score-based algorithms are developed for causal structure learning. Extensive synthetic experiments as well as a real dataset with known ground truth demonstrate the superior performance of the proposed method against state-of-the-art alternative methods in discovering causal structure from observational zero-inflated count data. An application of reverse-engineering a gene regulatory network from a single-cell RNA-sequencing dataset illustrates the utility of ZiG-DAGs in practice.

tags:
- Bayesian network
- Causal identifiability
- Directed acyclic graph
- Observational zero-inflated count data
- Single-cell RNA-sequencing
featured: true

links:
- name: R package
  url: 'https://github.com/junsoukchoi/ZiGDAG'
url_pdf: ''
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
