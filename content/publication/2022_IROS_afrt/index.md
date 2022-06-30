---
title: "ResamplingNet: End-to-End Adaptive Feature Resampling Network for Real-Time Aerial Tracking"
authors:
- Haobo Zuo
- Changhong Fu
- Sihang Li
- admin
- Guangze Zheng

date: "2022-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).意思是网页将上线的时间
publishDate: "2022-06-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Kyoto, Japan, pp. 1-8, 2022. 
publication_short: "IROS 2022"

abstract: Object feature pollution is one of the burning issues in UAV tracking, which is commonly caused by occlusion, fast motion, and illumination variation. Due to the contaminated information in the polluted object features, most trackers fail to precisely estimate the location and scale of the object. To address the feature pollution issue, this work proposes an efficient and effective adaptive feature resampling tracker, i.e., AFRT. AFRT mainly includes two stages, an adaptive downsampling network which can reduce the interference information of the feature pollution and a super-resolution upsampling network, applying Transformer to restore the object scale information. Specifically, the adaptive downsampling network strengthens the expression of the object location information, with a feature enhancement downsampling (FED) module. In order to achieve better training effect, a novel pooling distance loss function is designed to help FED module focus on the critical regions with the object information. Thereby, the features downsampled can be validly exploited to determine the location of the object. Subsequently, the super-resolution upsampling network raises the scale information in the features with a low-to-high (LTH) Transformer encoder. Exhaustive experiments on three well-known benchmarks validate the effectiveness of AFRT, especially on the sequences with feature pollution. In addition, real-world tests show the efficiency of AFRT with 31.4 frames per second. The code and demo videos are available at https://github.com/vision4robotics/AFRT.
# Summary. An optional shortened abstract.
# 

tags:
- Adaptive Feature Resampling
- UAV tracking
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ''
url_code: https://github.com/vision4robotics/AFRT
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/AFRT
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
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