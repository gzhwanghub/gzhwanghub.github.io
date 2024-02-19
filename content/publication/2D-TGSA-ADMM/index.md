---
title: 'Communication-efficient ADMM-based distributed algorithms for sparse training'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guozheng Wang 
  - Yongmei Lei 
  - Yongwen Qiu
  - Lingfei Lou
  - Yixin Li

# Author notes (optional)
# author_notes:
#  - ' '
#  - 'Corresponding author'

date: '2023-06-21'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-21'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing*
publication_short: In *Neurocomputing*

abstract: In large-scale distributed machine learning (DML), the synchronization efficiency of the distributed algorithm becomes a critical factor that affects the training time of machine learning models as the computing scale increases. To address this challenge, we propose a novel algorithm called Grouped Sparse AllReduce based on the 2D-Torus topology (2D-TGSA), which enables constant transmission traffic that does not change with the number of workers. Our experimental results demonstrate that 2D-TGSA outperforms several benchmark algorithms in terms of synchronization efficiency. Moreover, we integrate the general form consistent ADMM with 2D-TGSA to develop a distributed algorithm (2D-TGSA-ADMM) that exhibits excellent scalability and can effectively handle large-scale distributed optimization problems. Furthermore, we enhance 2D-TGSA-ADMM by adopting the resilient adaptive penalty parameter approach, resulting in a new algorithm called 2D-TGSA-TPADMM. Our experiments on training the logistic regression model with ‘1 -norm on the Tianhe-2 supercomputing platform demonstrate that our proposed algorithm can significantly reduce the synchronization time and training time compared to state-of-the-art methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

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

 Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https:// 
 docs.hugoblox.com/content/writing-markdown-latex/).
