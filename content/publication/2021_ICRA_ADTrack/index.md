---
title: "ADTrack: Target-Aware Dual Filter Learning for Real-Time Anti-Dark UAV Tracking"
authors:
- Bowen Li
- Changhong Fu
- Fangqiang Ding
- admin
- Fuling Lin

date: "2021-02-28T08:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-28T08:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), Xi'an, China, pp.496-502, 2021.
publication_short: In *ICRA2021*

abstract: Prior correlation filter (CF)-based tracking methods for unmanned aerial vehicles (UAVs) have virtually focused on tracking in the daytime. However, when the night falls, the trackers will encounter more harsh scenes, which can easily lead to tracking failure. In this regard, this work proposes a novel tracker with anti-dark function (ADTrack). The proposed method integrates an effcient and effective low-light image enhancer into a CF-based tracker. Besides, a target-aware mask is simultaneously generated by virtue of image illumination variation. The target-aware mask can be applied to jointly train a target-focused filter that assists the context filter for robust tracking. Specifically, ADTrack adopts dual regression, where the context filter and the target-focused filter restrict each other for dual filter learning. Exhaustive experiments are conducted on typical dark sceneries benchmark, consisting of 37 typical night sequences from authoritative benchmarks, i.e., UAVDark, and our newly constructed benchmark UAVDark70. The results have shown that ADTrack favorably outperforms other state-of-the-art trackers and achieves a real-time speed of 34 frames/s on a single CPU, thus greatly extending robust UAV tracking to night scenes.

# Summary. An optional shortened abstract.
# 

tags:
- Visual tracking
- Unmanned aerial vehicles
- Correlation filter
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2106.02495
url_code: https://github.com/vision4robotics/ADTrack
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/8ZnGOwoqDZ8

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: true

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
# <center>
# ![MKCT_workflow](featured.png)
# <small>Overall framework of the proposed ADTrack. ADTrack includes 3 stages: pretreatment, training, and detection, which are marked out by boxes in different colors. Dual filters, i.e., context filter and target-focused filter, training and detection follow routes in different colors. It can be seen that the final response shaded noises in context response, which indicates the validity of proposed dual filter.</small>


# </center>
---

