---
title: 'A Communication Efficient ADMM‑based Distributed Algorithm Using Two‑Dimensional Torus Grouping AllReduce'

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

date: '2023-01-02'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-02'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

publication_types: ["article-journal"]
# ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Data Science and Engineering*
publication_short: In *DSE*

abstract: Large-scale distributed training mainly consists of sub-model parallel training and parameter synchronization. With the expansion of training workers, the efficiency of parameter synchronization will be affected. To tackle this problem, we first propose 2D-TGA, a grouping AllReduce method based on the two-dimensional torus topology. This method synchronizes the model parameters by grouping and makes full use of bandwidth. Secondly, we propose a distributed algorithm, 2D-TGA-ADMM, which combines the 2D-TGA with the alternating direction method of multipliers (ADMM). It focuses on sub-model training and reduces the wait time among workers in the synchronization process. Finally, experimental results on the Tianhe-2 supercomputing platform show that compared with the 𝙼𝙿𝙸_𝙰𝚕𝚕𝚛𝚎𝚍𝚞𝚌𝚎, the 2D-TGA could shorten the synchronization wait time by 33%.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s41019-022-00202-7'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
