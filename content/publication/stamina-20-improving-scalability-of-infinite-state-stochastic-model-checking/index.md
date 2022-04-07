---
title: 'STAMINA 2.0: Improving Scalability of Infinite-State Stochastic Model Checking'
authors:
  - Riley Roberts
  - Thakur Neupane
  - LukasBuecherl
  - ChrisMyers
  - ZhenZhang
date: '2022-01-14'
doi: 'https://doi.org/10.1007/978-3-030-94583-1_16'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: International Conference on Verification, Model Checking, and Abstract Interpretation
publication_short: At *VMCAI 2022*

abstract: Stochastic model checking (SMC) is a formal verification technique for the analysis of systems with probabilistic behavior. Scalability has been a major limiting factor for SMC tools to analyze real-world systems with large or infinite state spaces. The infinite-state Continuous-time Markov Chain (CTMC) model checker, STAMINA, tackles this problem by selectively exploring only a portion of a model’s state space, where a majority of the probability mass resides, to efficiently give an accurate probability bound to properties under verification. In this paper, we present two major improvements to STAMINA, namely, a method of calculating and distributing estimated state reachability probabilities that improves state space truncation efficiency and combination of the previous two CTMC analyses into one for generating the probability bound. Demonstration of the improvements on several benchmark examples, including hazard analysis of infinite-state combinational genetic circuits, yield significant savings in both run-time and state space size (and hence memory), compared to both the previous version of STAMINA and the infinite-state CTMC model checker INFAMY. The improved STAMINA demonstrates significant scalability to allow for the verification of complex real-world infinite-state systems.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - stochastic model checking
  - infinite-state systems
  - markov chains
  - synthetic biology
featured: true

links:
#  - name: Custom Link
#    url: http://example.org
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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
slides:
---
