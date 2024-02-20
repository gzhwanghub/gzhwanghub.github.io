---
title: "Distributed ADMM Based on Sparse Computation and Allreduce Communication"
authors:
- Zeyu Zhang
- Yongmei Lei
- Dongxia Wang
- Guozheng Wang
date: "2023-03-23"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-23"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: " 2021 IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom)"
publication_short: "ISPA"

abstract: The distributed alternating direction method of mul-tipliers (ADMM) is an effective algorithm to solve large-scale op-timization problems. However, there are still massive computation and communication cost in distributed ADMM when processing high-dimensional data. To solve this problem, we propose a distributed ADMM with sparse computation and Allreduce communication (SCAC-ADMM) which can process high-dimensional data effectively. In the algorithm, each node optimizes a sub-model of the target model in parallel. Then, the target model is obtained by aggregating all sub-models. The features in the sub-model are named associated features. In SCAC-ADMM, we first design a selecting method of associated features to determine the composition of each sub-model. This method can limit the dimension of the sub-model by setting appropriate parameters, so as to limit the computation cost. Secondly, to reduce the communication traffic caused by transmitting high-dimensional parameters, we propose a novel Allreduce communication model which can only aggregate associated parameters in sub-models. Experiments on high-dimensional datasets show that SCAC-ADMM has less computation cost and higher communication efficiency than traditional distributed ADMM. When solving large-scale logistic regression problem, SCAC-ADMM can reduce the system time by 73% compared with traditional distributed ADMM.

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