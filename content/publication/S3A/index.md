---
title: "S3A: Towards Realistic Zero-Shot Classification via Self Structural Semantic Alignment"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
 - Sheng Zhang
 - admin
 - Guangyi Chen
 - Zhiqiang Shen
 - Salman Khan
 - Kun Zhang
 - Fahad Shahbaz Khan

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"


date: "2023-12-12T00:00:02Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-09-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * The Association for the Advancement of Artificial Intelligence, AAAI 2024*
publication_short: In *AAAI*

abstract: "Large scale pre trained Vision Language Models (VLMs) have proven effective for zero shot classification. Despite the success, most traditional VLMs based methods are restricted by the assumption of partial source supervision or ideal target vocabularies, which rarely satisfy the open world scenario. In this paper, we aim at a more challenging setting, Realistic Zero Shot Classification, which assumes no annotation but instead a broad vocabulary. To address the new problem, we propose the Self Structural Semantic Alignment (S3A) framework, which extracts the structural semantic information from unlabeled data while simultaneously self learning. Our S3A framework adopts a unique Cluster Vote Prompt Realign (CVPR) algorithm, which iteratively groups unlabeled data to derive structural semantics for pseudo-supervision. Our CVPR algorithm includes iterative clustering on images, voting within each cluster to identify initial class candidates from the vocabulary, generating discriminative prompts with large language models to discern confusing candidates, and realigning images and the vocabulary as structural semantic alignment. Finally, we propose to self train the CLIP image encoder with both individual and structural semantic alignment through a teacher-student learning strategy. Our comprehensive experiments across various generic and fine grained benchmarks demonstrate that the S3A method substantially improves over existing VLMs based approaches, achieving a more than 15% accuracy improvement over CLIP on average."

# Summary. An optional shortened abstract.
summary: <span style="font-size:120%;color:#117A65">**AAAI 2024**</span>, <span style="font-size:120%;color:#D35400">**Oral**</span> <br> Self-structural Alignment of Foundational Models for Zero-Shot.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Code
   url: https://github.com/sheng-eatamath/S3A
 - name: arXiv
   url: https://arxiv.org/abs/2308.12960

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

