---
title: 'Stochastic Hazard Analysis of Genetic Circuits in iBioSim and STAMINA'
authors:
  - Joshua Jeppson
  - Matthias Volk
  - Bryant Israelsen
  - Riley Roberts
  - Andrew Williams
  - Lukas Buecherl
  - Chris J. Myers
  - Hao Zhang
  - Chris Winstead
  - Zhen Zhang

#author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'
  #- 'Equal contribution'
date: '2023-15-09'
doi: '10.1007/978-3-031-43835-6_7'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'QUantitative Evaluation of SysTems'
publication_short: 'QEST'23'

abstract: Improving the scalability of probabilistic model checking (PMC) tools is crucial to the verification of real-world system designs. The Stamina infinite-state PMC tool achieves scalability by iteratively constructing a partial state space for an unbounded continuous-time Markov chain model, where a majority of the probability mass resides. It then performs time-bounded transient PMC. It can efficiently produce an accurate probability bound to the property under verification. We present a new software architecture design and the C++ implementation of the Stamina 2.0 algorithm, integrated with the Storm model checker. This open-source Stamina implementation offers a high degree of modularity and provides significant optimizations to the Stamina 2.0 algorithm. Performance improvements are demonstrated on multiple challenging benchmark examples, including hazard analysis of infinite-state combinational genetic circuits, over the previous Stamina implementation. Additionally, its design allows for future customizations and optimizations to the Stamina algorithm.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - markov chains
  - infinite state models
  - genetic circuits
  - hazards and glitches
  - synthetic biology
  - model verification
  - probabilistic model checking
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: 'https://github.com/fluentverification/stamina'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
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
