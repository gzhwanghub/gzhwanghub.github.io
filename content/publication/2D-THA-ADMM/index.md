---
title: '2D-THA-ADMM: communication efficient distributed ADMM algorithm framework based on two-dimensional torus hierarchical AllReduce'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guozheng Wang
  - Yongmei Lei
  - Zeyu Zhang
  - Cunlu Peng

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-06-10'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-10'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Machine Learning and Cybernetics*
publication_short: In *IJMLC*

abstract: Model synchronization refers to the communication process involved in large-scale distributed machine learning tasks. As the cluster scales up, the synchronization of model parameters becomes a challenging task that has to be coordinated among thousands of workers. Firstly, this study proposes a hierarchical AllReduce algorithm structured on a two-dimensional torus (2D-THA), which utilizes a hierarchical structure to synchronize model parameters and maximize bandwidth utilization. Secondly, this study introduces a distributed consensus algorithm called 2D-THA-ADMM, which combines the 2D-THA synchronization algorithm with the alternating direction method of multipliers (ADMM). Thirdly, we evaluate the model parameter synchronization performance of 2D-THA and the scalability of 2D-THA-ADMM on the Tianhe-2 supercomputing platform using real public datasets. Our experiments demonstrate that 2D-THA significantly reduces synchronization time by 63.447% compared to MPI_Allreduce. Furthermore, the proposed 2D-THA-ADMM algorithm exhibits excellent scalability, with a training speed increase of over 3× compared to the state-of-the-art methods, while maintaining high accuracy and computational efficiency.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
