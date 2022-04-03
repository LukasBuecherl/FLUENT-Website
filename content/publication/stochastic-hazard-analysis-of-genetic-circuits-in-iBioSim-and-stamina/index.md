---
title: 'Stochastic Hazard Analysis of Genetic Circuits in iBioSim and STAMINA'
authors:
  - LukasBuecherl
  - Riley Roberts
  - Pedro Fontanarrosa
  - PaytonThomas
  - Jeanet Mante
  - ZhenZhang
  - ChrisMyers

#author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'
  #- 'Equal contribution'
date: '2021-10-04'
doi: '10.1021/acssynbio.1c00159'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'ACS Synthetic Biology'
publication_short: 'ACS Synth. Biol.'

abstract: In synthetic biology, combinational circuits are used to program cells for various new applications like biosensors, drug delivery systems, and biofuels. Similar to asynchronous electronic circuits, some combinational genetic circuits may show unwanted switching variations (_glitches_) caused by multiple input changes. Depending on the biological circuit, glitches can cause irreversible effects and jeopardize the circuit’s functionality. This paper presents a stochastic analysis to predict glitch propensities for three implementations of a genetic circuit with known glitching behavior. The analysis uses _STochastic Approximate Model-checker for INfinite-state Analysis_ (STAMINA), a tool for stochastic verification. The STAMINA results were validated by comparison to stochastic simulation in iBioSim resulting in further improvements of STAMINA. This paper demonstrates that stochastic verification can be utilized by genetic designers to evaluate design choices and input restrictions to achieve a desired reliability of operation.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - genetic regulatory networks
  - genetic circuits
  - hazards and glitches
  - synthetic biology
  - model verification
  - stochastic simulation
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
image:
  caption: '' #'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
