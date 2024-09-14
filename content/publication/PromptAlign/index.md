---
title: "Align Your Prompts: Test-Time Prompting with Distribution Alignment for Zero-Shot Generalization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
 - Jameel Hassan
 - Hanan Gani
 - Noor Hussein
 - Muhammad Uzair Khattak
 - admin
 - Salman Khan
 - Fahad Shahbaz Khan

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"


date: "2023-11-12T00:00:02Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-09-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * Neural Information Processing Systems, NeurIPS 2023*
publication_short: In *NeurIPS*

abstract: "The promising zero-shot generalization of vision-language models such as CLIP
has led to their adoption using prompt learning for numerous downstream tasks.
Previous works have shown test time prompt tuning using entropy minimization
to adapt text prompts for unseen domains. While effective, this overlooks the
key cause for performance degradation to unseen domains – distribution shift. In
this work, we explicitly handle this problem by aligning the out-of-distribution
(OOD) test sample statistics to those of the source data using prompt tuning. We
use a single test sample to adapt multi modal prompts at test time by minimizing
the feature distribution shift to bridge the gap in the test domain. Evaluating
against the domain generalization benchmark, our method improves zero-shot top1 accuracy beyond existing prompt-learning techniques, with a 3.08% improvement
over the baseline MaPLe. In cross-dataset generalization with unseen categories
across 10 datasets, our method improves consistently across all datasets compared
to the existing state of the art. Our source code and models are available at
https://jameelhassan.github.io/promptalign/."

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#ff5733 ">**Vision-Language Model**</span>, <span style="font-size:120%;color:#117A65">**NeurIPS 2023**</span> <br> Test-Time Alignment of Foundational Models for Zero-shot.
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: Code
   url: https://github.com/jameelhassan/PromptAlign
 - name: arXiv
   url: https://arxiv.org/abs/2311.01459
 - name: Project
   url: https://jameelhassan.github.io/promptalign/
 - name: Video Presentation
   url: https://recorder-v3.slideslive.com/#/share?share=89606&s=2a435db5-fe74-47ff-91fc-f904a679f44d
 - name: Poster
   url: https://jameelhassan.github.io/promptalign/static/images/poster.png

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
# example

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

