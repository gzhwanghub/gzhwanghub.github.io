---
title: "HSAC-ALADMM: an asynchronous lazy ADMM algorithm based on hierarchical sparse allreduce communication"
authors:
- Dongxia Wang  
- Yongmei Lei  
- Jinyang Xie  
- Guozheng Wang 
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-01-14"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-14"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "The Journal of Supercomputing "
publication_short: "TJSC"

abstract: 'The distributed alternating direction method of multipliers (ADMM) is an effective algorithm for solving large-scale optimization problems. However, its high communication cost limits its scalability. An asynchronous lazy ADMM algorithm based on hierarchical sparse allreduce communication mode (HSAC-ALADMM) is proposed to reduce the communication cost of the distributed ADMM: firstly, this paper proposes a lazily aggregate parameters strategy to filter the transmission parameters of the distributed ADMM, which reduces the payload of the node per iteration. Secondly, a hierarchical sparse allreduce communication mode is tailored for sparse data to aggregate the filtered transmission parameters effectively. Finally, a Calculator-Communicator-Manager framework is designed to implement the proposed algorithm, which combines the asynchronous communication protocol and the allreduce communication mode effectively. It separates the calculation and communication by multithreading, thus improving the efficiency of system calculation and communication. Experimental results for the L1-regularized logistic regression problem with public datasets show that the HSAC-ALADMM algorithm is faster than existing asynchronous ADMM algorithms. Compared with existing sparse allreduce algorithms, the hierarchical sparse allreduce algorithm proposed in this paper makes better use of the characteristics of sparse data to reduce system time in multi-core cluster.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
