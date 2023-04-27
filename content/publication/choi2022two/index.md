---
title: "Two-Sample Bayesian Causal Directed Acyclic Graphs for Observational Zero-Inflated Count Data"
authors:
- admin
- Robert S. Chapkin
- Yang Ni
date: "2023-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "submitted. <br/> **[Winner of the ASA Section on Bayesian Statistical Science (SBSS) student paper award]**"
publication_short: ""

abstract: Observational zero-inflated count data arise in a wide range of areas such as economics, social sciences, and biology. One of the common research questions in these areas is to identify causal relationships by learning the structure of a sparse directed acyclic graph (DAG). While structure learning of DAGs has been an active research area, existing methods do not adequately account for excessive zeros and therefore are not suitable for modeling zero-inflated count data. Moreover, in many scientific settings, it is often interesting to study the differences in the causal networks for data collected from two experimental groups (control vs treatment). To explicitly account for zero-inflation and identify differential causal networks, we propose a novel Bayesian differential zero-inflated negative binomial DAG (DAG0) model. Our main theorem proves that the causal relationships under the proposed DAG0 are fully identifiable for purely observational, cross-sectional data, using a fairly general proof technique that is applicable beyond the proposed model. Bayesian inference based on parallel-tempered Markov chain Monte Carlo is developed to efficiently explore the multi-modal posterior landscape. We demonstrate the utility of the proposed DAG0 by comparing it with state-of-the-art alternative DAG methods using extensive simulations and real-data validation with known causal relationships. An application in single-cell RNA-sequencing dataset generated under two experimental groups finds some interesting results that appear to be consistent with existing knowledge

tags:
- Bayesian network
- Causal identifiability theory
- Differential network
- Parallel tempering
- Single-cell RNA-sequencing
featured: true

links:
- name: R package
  url: 'https://github.com/junsoukchoi/BayesDAG0'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
