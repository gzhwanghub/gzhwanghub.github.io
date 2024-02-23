---
title: "An efficient hybrid MPI/OpenMP parallelization of the asynchronous ADMM algorithm"
authors:
- Qinnan Qiu
- Yongmei Lei
- Dongxia Wang
- Guozheng Wang
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ' '  
date: "2021-09-30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-30"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: " 2021 IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom)"
publication_short: "ISPA"

abstract: Alternating direction method of multipliers (ADMM) is an efficient algorithm to solve large-scale machine learning problems in a distributed environment. To make full use of the hierarchical memory model in modern high-performance computing systems, this paper implements a hybrid MPI/OpenMP parallelization of the asynchronous ADMM algorithm (AH-ADMM). The AH-ADMM algorithm updates local variables in parallel by OpenMP threads and exchanges information between MPI processes, which relieves memory and communication pressure by replacing multi-processing with multi-threading. Furthermore, for the SVM problem, the AH-ADMM algorithm speeds up the calculation of sub-problems through an efficient parallel optimization strategy. This paper effectively combines the features of both algorithm design and programming model. Experiments on the Ziqiang4000 high-performance cluster demonstrate that the AH-ADMM algorithm scales better and run faster than the existing distributed ADMM algorithms implemented by pure MPI. The AH-ADMM can reduce the communication overhead by up to 91.8% and increase the convergence rate by up to 36x. For large datasets, the AH-ADMM can scale well on the cluster which over 129 cores.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: ''
url_code: 'https://github.com/gzhwanghub/ICSA-SHU/tree/main/AH-ADMM'
url_dataset: 'https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

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
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).