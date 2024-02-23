---
title: "Gr-admm: A communication efficient algorithm based on admm"
authors:
- Xin Huang
- Guozheng Wang
- Yongmei Lei
# Author notes (optional)
author_notes:
  - ''
  - ' '
  - ''  
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

abstract: In recent work, the decentralized algorithm has received more attention. In the centralized network, the worker nodes need to communicate with the central nodes, which results in the growth of communication traffic with the network expansion. Based on the purpose of reducing the communication costs in the distributed system, we proposed a decentralized algorithm based on ADMM - Grouping Ring All-Reduce ADMM (GR-ADMM) in this paper. First, GR-ADMM adopts decentralized architecture to avoid the problem of communication bottleneck in the central network. Second, to ensure the scalability of the distributed system, GR-ADMM introduces the Ring All-Reduce to the ADMM. Ring All-Reduce architecture has the advantage of its constant communication overhead. However, its performance is bounded by the stragglers (i.e., slow nodes). Third, GR-ADMM adopts the grouping strategy to alleviate the problem of stragglers. Experiments show that our algorithm has better convergence performance than QSGD and GADMM, especially in massive clusters. Compared with GADMM's, the overall communication cost of GR-ADMM is reduced by 72%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
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