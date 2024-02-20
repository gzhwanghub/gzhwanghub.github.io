---
title: "PSRA-HGADMM: A Communication Efficient Distributed ADMM Algorithm"
authors:
- Yongwen Qiu 
- Yongmei Lei 
- Guozheng Wang
date: "2023-08-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-07"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "52nd International Conference on Parallel Processing"
publication_short: "ICPP"

abstract: Among distributed machine learning algorithms, the global consensus alternating direction method of multipliers (ADMM) has attracted much attention because it can effectively solve large-scale optimization problems. However, the high communication cost slows its convergence and limits scalability. To solve the problem, we propose a hierarchical grouping ADMM algorithm (PSRA-HGADMM) with a novel Ring-Allreduce communication model in this paper. Firstly, we optimize the parameter exchange of the ADMM algorithm and implement the global consensus ADMM algorithm in the decentralized architecture. Secondly, to improve the communication efficiency of the distributed system, we propose a novel Ring-Allreduce communication model (PSR-Allreduce) based on the idea of parameter server architecture. Finally, a Worker-Leader-Group generator (WLG) framework is designed to solve the problem of inconsistency of cluster nodes. This framework combines hierarchical parameter aggregation and adopts the grouping strategy to improve the scalability of the distributed system. Experiments show that PSRA-HGADMM has better convergence performance and better scalability than ADMMLib and AD-ADMM. Compared with ADMMLib, the overall communication cost of PSRA-HGADMM is reduced by 32%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: ''
url_code: 'https://github.com/gzhwanghub/ICSA-SHU'
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